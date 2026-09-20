<script>
import Icon from '@iconify/css-svelte';
import '../../css/j/jz_2umrfg.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="jz_2umrfg"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="mdi:guitar-pick-outline" {...props}></Icon>
