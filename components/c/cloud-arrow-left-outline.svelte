<script>
import Icon from '@iconify/css-svelte';
import '../../css/b/bgbijcq9k.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="bgbijcq9k"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="mdi:cloud-arrow-left-outline" {...props}></Icon>
