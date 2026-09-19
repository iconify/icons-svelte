<script>
import Icon from '@iconify/css-svelte';
import '../../css/i/ipq1z-bjh.css';
import '../../css/f/fe236rbzs.css';
import '../../css/f/f395o7-qj.css';
import '../../css/b/b6u2wybtn.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="ipq1z-bjh"><path class="fe236rbzs"/><path class="f395o7-qj"/><path class="b6u2wybtn"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="iconoir:group" {...props}></Icon>
