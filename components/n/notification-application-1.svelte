<script>
import Icon from '@iconify/css-svelte';
import '../../css/u/u6lsl9b2u.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":14,"height":14};
const content = `<path class="u6lsl9b2u"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="streamline-flex:notification-application-1" {...props}></Icon>
