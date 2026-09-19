<script>
import Icon from '@iconify/css-svelte';
import '../../css/f/ft5dv1b6b.css';
import '../../css/n/n1h1nwbtk.css';
import '../../css/f/fi6t_s8wt.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":32,"height":32};
const content = `<g class="ft5dv1b6b"><circle class="n1h1nwbtk"/><path class="fi6t_s8wt"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="cryptocurrency-color:dock" {...props}></Icon>
