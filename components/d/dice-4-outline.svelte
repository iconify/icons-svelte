<script>
import Icon from '@iconify/css-svelte';
import '../../css/k/kd0csib2x.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="kd0csib2x"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="mdi:dice-4-outline" {...props}></Icon>
