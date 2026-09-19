<script>
import Icon from '@iconify/css-svelte';
import '../../css/v/vmg_qxorr.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":1200,"height":1200};
const content = `<path class="vmg_qxorr"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="el:hdd" {...props}></Icon>
