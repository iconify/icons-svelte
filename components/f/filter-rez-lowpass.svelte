<script>
import Icon from '@iconify/css-svelte';
import '../../css/j/jz2bgzbvc.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":256,"height":256};
const content = `<path class="jz2bgzbvc"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="fad:filter-rez-lowpass" {...props}></Icon>
