<script>
import Icon from '@iconify/css-svelte';
import '../../css/v/vav2w_v0u.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="vav2w_v0u"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="grommet-icons:location-pin" {...props}></Icon>
