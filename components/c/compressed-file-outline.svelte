<script>
import Icon from '@iconify/css-svelte';
import '../../css/l/lm59u6zwt.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="lm59u6zwt"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="mdi:compressed-file-outline" {...props}></Icon>
