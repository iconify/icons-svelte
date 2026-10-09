<script>
import Icon from '@iconify/css-svelte';
import '../../css/t/tbnuryord.css';
import '../../css/d/ddoez_smv.css';
import '../../css/z/z36fjojcj.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":48,"height":48};
const content = `<path class="tbnuryord"/><path class="ddoez_smv"/><path class="z36fjojcj"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="energy-icons:inspection-48" {...props}></Icon>
