<script>
import Icon from '@iconify/css-svelte';
import '../../css/r/rzdcbjbtp.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path class="rzdcbjbtp"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="ion:notifications-sharp" {...props}></Icon>
