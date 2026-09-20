<script>
import Icon from '@iconify/css-svelte';
import '../../css/l/larysibsv.css';
import '../../css/i/ij2x_72vy.css';
import '../../css/d/dop23ibmn.css';
import '../../css/t/tkfk-sbea.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":72,"height":72};
const content = `<circle class="larysibsv"/><g class="ij2x_72vy"><circle class="dop23ibmn"/><path class="tkfk-sbea"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="openmoji:dim-button" {...props}></Icon>
