<script>
import Icon from '@iconify/css-svelte';
import '../../css/i/ipq1z-bjh.css';
import '../../css/c/cmps53bym.css';
import '../../css/v/vfu_1b34a.css';
import '../../css/a/a0qpe2bov.css';
import '../../css/z/zwovzli5u.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="ipq1z-bjh"><path class="cmps53bym"/><path class="vfu_1b34a"/><path class="a0qpe2bov"/><path class="zwovzli5u"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="iconoir:repository" {...props}></Icon>
