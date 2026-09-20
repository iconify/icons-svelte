<script>
import Icon from '@iconify/css-svelte';
import '../../css/f/flen3tbdj.css';
import '../../css/t/te85glbsz.css';
import '../../css/e/emnsetb8o.css';
import '../../css/t/ts76sqbbo.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="flen3tbdj"><rect transform="rotate(-90 15 9)" class="te85glbsz"/><path class="emnsetb8o"/><path class="ts76sqbbo"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="lets-icons:line-in-alt" {...props}></Icon>
