<script>
import Icon from '@iconify/css-svelte';
import '../../css/i/iz32weafm.css';
import '../../css/t/tawx_qbnz.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":64,"height":64};
const content = `<path class="iz32weafm"/><path class="tawx_qbnz"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="lineicons:circle-minus" {...props}></Icon>
