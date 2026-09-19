<script>
import Icon from '@iconify/css-svelte';
import '../../css/h/hpzgadc_j.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":432,"height":432};
const content = `<path class="hpzgadc_j"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="zmdi:linkedin" {...props}></Icon>
