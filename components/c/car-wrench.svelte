<script>
import Icon from '@iconify/css-svelte';
import '../../css/q/qoo82bpzy.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":16,"height":16};
const content = `<path class="qoo82bpzy"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="roentgen:car-wrench" {...props}></Icon>
