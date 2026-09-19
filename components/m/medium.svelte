<script>
import Icon from '@iconify/css-svelte';
import '../../css/j/jx0p4fbya.css';
import '../../css/l/l7z6dbf4g.css';
import '../../css/j/jfx8o0b0z.css';
import '../../css/o/oz-lqwbam.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="jx0p4fbya"><circle class="l7z6dbf4g"/><ellipse class="jfx8o0b0z"/><ellipse class="oz-lqwbam"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="hugeicons:medium" {...props}></Icon>
