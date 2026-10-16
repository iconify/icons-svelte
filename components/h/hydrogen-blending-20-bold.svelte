<script>
import Icon from '@iconify/css-svelte';
import '../../css/k/ke-cmwbjg.css';
import '../../css/z/zthy_-bth.css';
import '../../css/r/r50nl1bwp.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":20,"height":20};
const content = `<path class="ke-cmwbjg"/><path class="zthy_-bth"/><path class="r50nl1bwp"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="energy-icons:hydrogen-blending-20-bold" {...props}></Icon>
