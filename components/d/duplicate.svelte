<script>
import Icon from '@iconify/css-svelte';
import '../../css/a/ah0t1lfzm.css';
import '../../css/u/ueiqpgber.css';
import '../../css/i/ij2x_72vy.css';
import '../../css/z/zxfhicblf.css';
import '../../css/o/o_fcpcc1g.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":72,"height":72};
const content = `<path class="ah0t1lfzm"/><path class="ueiqpgber"/><g class="ij2x_72vy"><path class="zxfhicblf"/><path class="o_fcpcc1g"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="openmoji:duplicate" {...props}></Icon>
