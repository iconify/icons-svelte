<script>
import Icon from '@iconify/css-svelte';
import '../../css/k/kkq6cdz7p.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="kkq6cdz7p"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="hugeicons:curvy-right-direction" {...props}></Icon>
