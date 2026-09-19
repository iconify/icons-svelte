<script>
import Icon from '@iconify/css-svelte';
import '../../css/f/ft5dv1b6b.css';
import '../../css/i/irabnhb9e.css';
import '../../css/j/jiz5zbbbs.css';
import '../../css/e/edo2a4sfe.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":80,"height":80};
const content = `<g class="ft5dv1b6b"><path class="irabnhb9e"/><path class="jiz5zbbbs"/><path class="edo2a4sfe"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="glyphs:cloudy-duo" {...props}></Icon>
