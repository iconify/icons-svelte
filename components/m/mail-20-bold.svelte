<script>
import Icon from '@iconify/css-svelte';
import '../../css/p/pn86m-bcf.css';
import '../../css/v/vvf4d-dpu.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":20,"height":20};
const content = `<path class="pn86m-bcf"/><path class="vvf4d-dpu"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="energy-icons:mail-20-bold" {...props}></Icon>
