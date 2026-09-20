<script>
import Icon from '@iconify/css-svelte';
import '../../css/y/ycq1qfcwy.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path clip-rule="evenodd" class="ycq1qfcwy"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="ix:machine-c" {...props}></Icon>
