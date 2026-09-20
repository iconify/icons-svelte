<script>
import Icon from '@iconify/css-svelte';
import '../../css/o/omgu7_bgj.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path class="omgu7_bgj"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="selfhst:microsoft-outlook-2000-light" {...props}></Icon>
