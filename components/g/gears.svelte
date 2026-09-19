<script>
import Icon from '@iconify/css-svelte';
import '../../css/c/cuyn6tgcc.css';
import '../../css/g/g2eg8ec2k.css';
import '../../css/r/rr7aclb4v.css';
import '../../css/n/nngyw5bfh.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":42,"height":32};
const content = `<g class="cuyn6tgcc"><path class="g2eg8ec2k"/><path class="rr7aclb4v"/><path class="nngyw5bfh"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="et:gears" {...props}></Icon>
