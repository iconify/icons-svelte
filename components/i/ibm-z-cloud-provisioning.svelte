<script>
import Icon from '@iconify/css-svelte';
import '../../css/z/zs_bqebbh.css';
import '../../css/m/m3lxbjutz.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":32,"height":32};
const content = `<path class="zs_bqebbh"/><path class="m3lxbjutz"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="carbon:ibm-z-cloud-provisioning" {...props}></Icon>
