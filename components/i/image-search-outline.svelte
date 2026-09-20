<script>
import Icon from '@iconify/css-svelte';
import '../../css/h/hj6o4wafj.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="hj6o4wafj"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="mdi:image-search-outline" {...props}></Icon>
