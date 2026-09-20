<script>
import Icon from '@iconify/css-svelte';
import '../../css/i/ia0plmbic.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="ia0plmbic"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="solar:crown-minimalistic-linear" {...props}></Icon>
