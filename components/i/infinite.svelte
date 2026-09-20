<script>
import Icon from '@iconify/css-svelte';
import '../../css/n/nwm8scbut.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":16,"height":16};
const content = `<path class="nwm8scbut"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="nimbus:infinite" {...props}></Icon>
