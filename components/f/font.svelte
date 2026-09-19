<script>
import Icon from '@iconify/css-svelte';
import '../../css/j/jkutg_bpc.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":448,"height":512};
const content = `<path class="jkutg_bpc"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="fa6-solid:font" {...props}></Icon>
