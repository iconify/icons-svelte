<script>
import Icon from '@iconify/css-svelte';
import '../../css/w/wez-d0bjf.css';
import '../../css/a/a3l3mwbwy.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="wez-d0bjf"/><path class="a3l3mwbwy"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="lineicons:mastercard" {...props}></Icon>
