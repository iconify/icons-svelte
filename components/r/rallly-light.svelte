<script>
import Icon from '@iconify/css-svelte';
import '../../css/b/b1lucj3yy.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path class="b1lucj3yy"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="selfhst:rallly-light" {...props}></Icon>
