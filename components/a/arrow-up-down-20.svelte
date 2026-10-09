<script>
import Icon from '@iconify/css-svelte';
import '../../css/b/burqsaclr.css';
import '../../css/z/zslpuabll.css';
import '../../css/m/mxw0qifka.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":20,"height":20};
const content = `<path class="burqsaclr"/><path class="zslpuabll"/><path class="mxw0qifka"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="energy-icons:arrow-up-down-20" {...props}></Icon>
