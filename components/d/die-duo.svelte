<script>
import Icon from '@iconify/css-svelte';
import '../../css/f/ft5dv1b6b.css';
import '../../css/g/g9y54obih.css';
import '../../css/v/vqj6j6upz.css';
import '../../css/w/www_habqm.css';
import '../../css/y/yufnd7b4z.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":80,"height":80};
const content = `<g class="ft5dv1b6b"><path class="g9y54obih"/><path class="vqj6j6upz"/><path class="www_habqm"/><path class="yufnd7b4z"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="glyphs:die-duo" {...props}></Icon>
