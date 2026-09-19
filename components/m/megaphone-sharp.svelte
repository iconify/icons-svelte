<script>
import Icon from '@iconify/css-svelte';
import '../../css/i/ixl6a-mcn.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path class="ixl6a-mcn"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="ion:megaphone-sharp" {...props}></Icon>
