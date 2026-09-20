<script>
import Icon from '@iconify/css-svelte';
import '../../css/t/ttdwwrvcu.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="ttdwwrvcu"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="mdi:briefcase-arrow-up-down-outline" {...props}></Icon>
