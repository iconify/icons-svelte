<script>
import Icon from '@iconify/css-svelte';
import '../../css/w/wm4zn8bfo.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path class="wm4zn8bfo"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="selfhst:eternal-vows-light" {...props}></Icon>
