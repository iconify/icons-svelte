<script>
import Icon from '@iconify/css-svelte';
import '../../css/t/tdyizyb3e.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path class="tdyizyb3e"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="famicons:notifications-off-circle-sharp" {...props}></Icon>
