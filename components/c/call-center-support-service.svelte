<script>
import Icon from '@iconify/css-svelte';
import '../../css/s/slquxucew.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":14,"height":14};
const content = `<path class="slquxucew"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="streamline:call-center-support-service" {...props}></Icon>
