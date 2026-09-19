<script>
import Icon from '@iconify/css-svelte';
import '../../css/f/ft5dv1b6b.css';
import '../../css/w/w6uetzpvg.css';
import '../../css/g/g75cc2fkj.css';
import '../../css/h/hsw65cfsq.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":32,"height":32};
const content = `<g class="ft5dv1b6b"><path class="w6uetzpvg"/><path class="g75cc2fkj"/><ellipse transform="rotate(30 23.477 12.594)" class="hsw65cfsq"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="fluent-emoji-flat:orange-heart" {...props}></Icon>
