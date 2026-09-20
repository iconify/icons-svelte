<script>
import Icon from '@iconify/css-svelte';
import '../../css/c/c9i8f50fi.css';
import '../../css/b/btdwznbdt.css';
import '../../css/i/ij2x_72vy.css';
import '../../css/m/mbnqul_uo.css';
import '../../css/g/g55uyl9fg.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":72,"height":72};
const content = `<path class="c9i8f50fi"/><path class="btdwznbdt"/><g class="ij2x_72vy"><path class="mbnqul_uo"/><path class="g55uyl9fg"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="openmoji:kissing-cat" {...props}></Icon>
