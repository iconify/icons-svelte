<script>
import Icon from '@iconify/css-svelte';
import '../../css/u/uugee_ckg.css';
import '../../css/b/b7_eq70_a.css';
import '../../css/i/ij2x_72vy.css';
import '../../css/c/cn8kflqeu.css';
import '../../css/e/eem25gbjx.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":72,"height":72};
const content = `<path class="uugee_ckg"/><path class="b7_eq70_a"/><g class="ij2x_72vy"><path class="cn8kflqeu"/><path class="eem25gbjx"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="openmoji:pig" {...props}></Icon>
