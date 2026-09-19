<script>
import Icon from '@iconify/css-svelte';
import '../../css/v/vsf_xwbsm.css';
import '../../css/q/qp7v_obxe.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":32,"height":32};
const content = `<path class="vsf_xwbsm"/><path class="qp7v_obxe"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="carbon:crop" {...props}></Icon>
