<script>
import Icon from '@iconify/css-svelte';
import '../../css/j/jivb_cbdx.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path class="jivb_cbdx"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="subway:redo-1" {...props}></Icon>
