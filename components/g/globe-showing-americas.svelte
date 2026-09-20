<script>
import Icon from '@iconify/css-svelte';
import '../../css/a/ae849gbxa.css';
import '../../css/s/sz-_5oksg.css';
import '../../css/v/vv6n5srqa.css';
import '../../css/i/ij2x_72vy.css';
import '../../css/u/usozxnbrm.css';
import '../../css/z/z-z_l7bta.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":72,"height":72};
const content = `<g class="ae849gbxa"><circle class="sz-_5oksg"/><path class="vv6n5srqa"/></g><g class="ij2x_72vy"><circle class="usozxnbrm"/><path class="z-z_l7bta"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="openmoji:globe-showing-americas" {...props}></Icon>
