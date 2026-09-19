<script>
import Icon from '@iconify/css-svelte';
import '../../css/j/j_u1exb-p.css';
import '../../css/h/hbx_zybzm.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":32,"height":32};
const content = `<path class="j_u1exb-p"/><path class="hbx_zybzm"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="carbon:ibm-security-services" {...props}></Icon>
