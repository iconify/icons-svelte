<script>
import Icon from '@iconify/css-svelte';
import '../../css/p/pzhxjnb-s.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="pzhxjnb-s"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="mdi:book-location-outline" {...props}></Icon>
