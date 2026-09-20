<script>
import Icon from '@iconify/css-svelte';
import '../../css/c/caldd_r-k.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="caldd_r-k"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="mdi:android-auto" {...props}></Icon>
