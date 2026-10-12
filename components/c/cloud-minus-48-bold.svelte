<script>
import Icon from '@iconify/css-svelte';
import '../../css/x/xv9xlxb3o.css';
import '../../css/h/hwjgqrbah.css';
import '../../css/t/tlvvk8-lt.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":48,"height":48};
const content = `<path class="xv9xlxb3o"/><path class="hwjgqrbah"/><path class="tlvvk8-lt"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="energy-icons:cloud-minus-48-bold" {...props}></Icon>
