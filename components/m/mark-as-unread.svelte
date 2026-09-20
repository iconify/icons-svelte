<script>
import Icon from '@iconify/css-svelte';
import '../../css/f/ft5dv1b6b.css';
import '../../css/e/etsfcbjxk.css';
import '../../css/c/cg17v90sw.css';
import '../../css/g/ghk1tgbqk.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="ft5dv1b6b"><path class="etsfcbjxk"/><path class="cg17v90sw"/><path class="ghk1tgbqk"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="tdesign:mark-as-unread" {...props}></Icon>
