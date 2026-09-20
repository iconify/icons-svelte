<script>
import Icon from '@iconify/css-svelte';
import '../../css/k/knso19jju.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="knso19jju"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="ri:menu-4-line" {...props}></Icon>
