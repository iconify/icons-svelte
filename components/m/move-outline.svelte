<script>
import Icon from '@iconify/css-svelte';
import '../../css/r/rl5mm0lik.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="rl5mm0lik"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="solar:move-outline" {...props}></Icon>
