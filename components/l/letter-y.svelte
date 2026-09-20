<script>
import Icon from '@iconify/css-svelte';
import '../../css/w/w84quwacf.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="w84quwacf"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="mdi:letter-y" {...props}></Icon>
