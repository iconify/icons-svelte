<script>
import Icon from '@iconify/css-svelte';
import '../../css/y/yw3xaacjo.css';
import '../../css/v/vr_lhqmel.css';
import '../../css/c/cxs9w9b4b.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":20,"height":20};
const content = `<path class="yw3xaacjo"/><path class="vr_lhqmel"/><path class="cxs9w9b4b"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="energy-icons:arrow-up-circle-20" {...props}></Icon>
