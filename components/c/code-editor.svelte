<script>
import Icon from '@iconify/css-svelte';
import '../../css/c/cshvsweet.css';
import '../../css/i/ij2x_72vy.css';
import '../../css/m/mfug5ibpq.css';
import '../../css/c/c66ezsb2m.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":72,"height":72};
const content = `<path class="cshvsweet"/><g class="ij2x_72vy"><path class="mfug5ibpq"/><path class="c66ezsb2m"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="openmoji:code-editor" {...props}></Icon>
