<script>
import Icon from '@iconify/css-svelte';
import '../../css/w/w80cq7bag.css';
import '../../css/g/g9n4ckv2m.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":32,"height":32};
const content = `<path class="w80cq7bag"/><path class="g9n4ckv2m"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="carbon:cics-region-routing" {...props}></Icon>
