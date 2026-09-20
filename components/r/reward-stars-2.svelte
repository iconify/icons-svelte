<script>
import Icon from '@iconify/css-svelte';
import '../../css/f/fosm35z7h.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="fosm35z7h"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="streamline-ultimate:reward-stars-2" {...props}></Icon>
