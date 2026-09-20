<script>
import Icon from '@iconify/css-svelte';
import '../../css/q/qyscnr3nm.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":16,"height":16};
const content = `<path class="qyscnr3nm"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="sidekickicons:gamepad-16-solid" {...props}></Icon>
