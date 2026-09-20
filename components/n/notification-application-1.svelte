<script>
import Icon from '@iconify/css-svelte';
import '../../css/l/lbk2hrbih.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":14,"height":14};
const content = `<path class="lbk2hrbih"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="streamline:notification-application-1" {...props}></Icon>
