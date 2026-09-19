<script>
import Icon from '@iconify/css-svelte';
import '../../css/m/mc3fdx9jx.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="mc3fdx9jx"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="hugeicons:repeat-off" {...props}></Icon>
