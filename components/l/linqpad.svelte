<script>
import Icon from '@iconify/css-svelte';
import '../../css/w/wl_5u-arg.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":485,"height":512};
const content = `<path class="wl_5u-arg"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="file-icons:linqpad" {...props}></Icon>
