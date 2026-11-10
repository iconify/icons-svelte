<script>
import Icon from '@iconify/css-svelte';
import '../../css/w/wb1x9obgy.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":20,"height":20};
const content = `<path clip-rule="evenodd" class="wb1x9obgy"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="sidekickicons:calendar-arrow-path-20-solid" {...props}></Icon>
