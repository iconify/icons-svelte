<script>
import Icon from '@iconify/css-svelte';
import '../../css/k/k1lodwb8w.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="k1lodwb8w"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="streamline-ultimate:concert-microphone-bold" {...props}></Icon>
