<script>
import Icon from '@iconify/css-svelte';
import '../../css/u/utwwo2jbm.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="utwwo2jbm"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="mdi:envelope-heart-outline" {...props}></Icon>
