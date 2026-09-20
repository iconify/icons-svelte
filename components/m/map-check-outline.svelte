<script>
import Icon from '@iconify/css-svelte';
import '../../css/z/zpx25pbdj.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="zpx25pbdj"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="mdi:map-check-outline" {...props}></Icon>
