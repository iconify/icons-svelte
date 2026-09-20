<script>
import Icon from '@iconify/css-svelte';
import '../../css/s/swm5vp20p.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="swm5vp20p"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="mdi:alpha-q-box-outline" {...props}></Icon>
