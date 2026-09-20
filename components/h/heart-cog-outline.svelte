<script>
import Icon from '@iconify/css-svelte';
import '../../css/t/t5vztwbvg.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="t5vztwbvg"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="mdi:heart-cog-outline" {...props}></Icon>
