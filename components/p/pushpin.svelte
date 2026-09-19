<script>
import Icon from '@iconify/css-svelte';
import '../../css/f/ft5dv1b6b.css';
import '../../css/p/p0cc53bau.css';
import '../../css/h/ha9j-vbrj.css';
import '../../css/d/dhr2l13no.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":32,"height":32};
const content = `<g class="ft5dv1b6b"><path class="p0cc53bau"/><path class="ha9j-vbrj"/><path class="dhr2l13no"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="fluent-emoji-flat:pushpin" {...props}></Icon>
