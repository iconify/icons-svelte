<script>
import Icon from '@iconify/css-svelte';
import '../../css/i/ipq1z-bjh.css';
import '../../css/z/zhx9aotxt.css';
import '../../css/u/u-sf_6btt.css';
import '../../css/g/g5rmplr5j.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="ipq1z-bjh"><path class="zhx9aotxt"/><path class="u-sf_6btt"/><path class="g5rmplr5j"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="iconoir:mail-in" {...props}></Icon>
