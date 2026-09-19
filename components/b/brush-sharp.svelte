<script>
import Icon from '@iconify/css-svelte';
import '../../css/b/b4nw8f58x.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path class="b4nw8f58x"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="ion:brush-sharp" {...props}></Icon>
