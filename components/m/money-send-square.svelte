<script>
import Icon from '@iconify/css-svelte';
import '../../css/i/ipq1z-bjh.css';
import '../../css/x/x7z8ft8ni.css';
import '../../css/q/qjyf55b-j.css';
import '../../css/e/eaoa-ybqh.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="ipq1z-bjh"><path class="x7z8ft8ni"/><path class="qjyf55b-j"/><path class="eaoa-ybqh"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="hugeicons:money-send-square" {...props}></Icon>
