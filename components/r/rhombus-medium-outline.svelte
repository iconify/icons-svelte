<script>
import Icon from '@iconify/css-svelte';
import '../../css/k/kjhj_nbzp.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="kjhj_nbzp"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="mdi:rhombus-medium-outline" {...props}></Icon>
