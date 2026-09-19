<script>
import Icon from '@iconify/css-svelte';
import '../../css/i/i3t-q0_bj.css';
import '../../css/g/gzhvap6lb.css';
import '../../css/r/rrgcllb8v.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="i3t-q0_bj"/><path class="gzhvap6lb"/><path class="rrgcllb8v"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="gcp:cloud-nat" {...props}></Icon>
