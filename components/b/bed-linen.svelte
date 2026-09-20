<script>
import Icon from '@iconify/css-svelte';
import '../../css/q/qzka1x0wa.css';
import '../../css/f/fjej9hboc.css';
import '../../css/c/cylywgbpa.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":72,"height":72};
const content = `<path class="qzka1x0wa"/><path class="fjej9hboc"/><path class="cylywgbpa"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="openmoji:bed-linen" {...props}></Icon>
