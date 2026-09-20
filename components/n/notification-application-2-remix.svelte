<script>
import Icon from '@iconify/css-svelte';
import '../../css/s/sxc27i0rm.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":14,"height":14};
const content = `<path clip-rule="evenodd" class="sxc27i0rm"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="streamline:notification-application-2-remix" {...props}></Icon>
