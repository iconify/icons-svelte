<script>
import Icon from '@iconify/css-svelte';
import '../../css/b/b8xl3h-3e.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path class="b8xl3h-3e"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="selfhst:doska-light" {...props}></Icon>
