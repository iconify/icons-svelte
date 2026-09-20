<script>
import Icon from '@iconify/css-svelte';
import '../../css/w/w1c1x8bar.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="w1c1x8bar"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="mdi:file-powerpoint-box" {...props}></Icon>
