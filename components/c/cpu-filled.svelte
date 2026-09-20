<script>
import Icon from '@iconify/css-svelte';
import '../../css/e/eccbwzb_m.css';
import '../../css/n/nq39egbbv.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="eccbwzb_m"/><path class="nq39egbbv"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="tdesign:cpu-filled" {...props}></Icon>
