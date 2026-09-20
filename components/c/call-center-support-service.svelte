<script>
import Icon from '@iconify/css-svelte';
import '../../css/u/uw5mlobsg.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":14,"height":14};
const content = `<path class="uw5mlobsg"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="streamline-flex:call-center-support-service" {...props}></Icon>
