<script>
import Icon from '@iconify/css-svelte';
import '../../css/t/tzyoq6bkv.css';
import '../../css/m/mhm-ij5vt.css';
import '../../css/x/xipv2cbae.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":48,"height":48};
const content = `<path class="tzyoq6bkv"/><path class="mhm-ij5vt"/><path class="xipv2cbae"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="energy-icons:lamp-48" {...props}></Icon>
