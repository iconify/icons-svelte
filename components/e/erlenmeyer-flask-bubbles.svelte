<script>
import Icon from '@iconify/css-svelte';
import '../../css/m/mz8smpd4d.css';
import '../../css/r/r0711mb5p.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path class="mz8smpd4d"/><path class="r0711mb5p"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="ion:erlenmeyer-flask-bubbles" {...props}></Icon>
