<script>
import Icon from '@iconify/css-svelte';
import '../../css/e/e18-09vcd.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path class="e18-09vcd"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="selfhst:opensuse-step-light" {...props}></Icon>
