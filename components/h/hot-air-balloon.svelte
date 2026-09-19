<script>
import Icon from '@iconify/css-svelte';
import '../../css/j/jx0p4fbya.css';
import '../../css/j/jx6yqbbhl.css';
import '../../css/s/smmxe_bdk.css';
import '../../css/h/hfshdjlhh.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="jx0p4fbya"><path class="jx6yqbbhl"/><path class="smmxe_bdk"/><path class="hfshdjlhh"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="iconoir:hot-air-balloon" {...props}></Icon>
