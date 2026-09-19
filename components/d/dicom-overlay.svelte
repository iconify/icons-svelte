<script>
import Icon from '@iconify/css-svelte';
import '../../css/r/r0109jbdn.css';
import '../../css/s/scn20qlnz.css';
import '../../css/z/zo89sabib.css';
import '../../css/o/oi9t13ngc.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":32,"height":32};
const content = `<path class="r0109jbdn"/><path class="scn20qlnz"/><path class="zo89sabib"/><path class="oi9t13ngc"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="carbon:dicom-overlay" {...props}></Icon>
