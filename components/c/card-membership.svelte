<script>
import Icon from '@iconify/css-svelte';
import '../../css/c/clabpwbmf.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="clabpwbmf"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="mdi:card-membership" {...props}></Icon>
