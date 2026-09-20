<script>
import Icon from '@iconify/css-svelte';
import '../../css/w/w747y2bgd.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="w747y2bgd"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="mdi:image-size-select-actual" {...props}></Icon>
