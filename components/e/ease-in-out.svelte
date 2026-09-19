<script>
import Icon from '@iconify/css-svelte';
import '../../css/i/ij8-ce7zs.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="ij8-ce7zs"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="hugeicons:ease-in-out" {...props}></Icon>
