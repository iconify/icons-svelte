<script>
import Icon from '@iconify/css-svelte';
import '../../css/f/ft5dv1b6b.css';
import '../../css/z/zdw9dcb7o.css';
import '../../css/h/h8g1-z1hm.css';
import '../../css/r/r50bwp4zp.css';
import '../../css/f/fa35vvbiv.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":256,"height":256};
const content = `<g class="ft5dv1b6b"><rect class="zdw9dcb7o"/><path class="h8g1-z1hm"/><path class="r50bwp4zp"/><path class="fa35vvbiv"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="skill-icons:julia-dark" {...props}></Icon>
