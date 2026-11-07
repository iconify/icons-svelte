<script>
import Icon from '@iconify/css-svelte';
import '../../css/i/ipq1z-bjh.css';
import '../../css/k/kr4evflrk.css';
import '../../css/p/pddlj0b6t.css';
import '../../css/j/joig5dakl.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="ipq1z-bjh"><path class="kr4evflrk"/><path class="pddlj0b6t"/><path class="joig5dakl"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="solar:dialog-linear" {...props}></Icon>
