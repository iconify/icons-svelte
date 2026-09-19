<script>
import Icon from '@iconify/css-svelte';
import '../../css/x/xc5ow5b6o.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":216,"height":384};
const content = `<path class="xc5ow5b6o"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="zmdi:caret-down" {...props}></Icon>
