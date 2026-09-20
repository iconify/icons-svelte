<script>
import Icon from '@iconify/css-svelte';
import '../../css/u/ueum36p4v.css';
import '../../css/c/cvp889bmc.css';
import '../../css/x/xaeykmbyl.css';
import '../../css/j/jn8qy4bru.css';
import '../../css/m/m26u0abhn.css';
import '../../css/a/a4o5ydhls.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":72,"height":72};
const content = `<path class="ueum36p4v"/><path class="cvp889bmc"/><path class="xaeykmbyl"/><g class="jn8qy4bru"><path class="m26u0abhn"/><path class="a4o5ydhls"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="openmoji:fortune-cookie" {...props}></Icon>
