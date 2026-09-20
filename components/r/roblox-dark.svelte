<script>
import Icon from '@iconify/css-svelte';
import '../../css/k/kmrgqeb6x.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path class="kmrgqeb6x"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="selfhst:roblox-dark" {...props}></Icon>
