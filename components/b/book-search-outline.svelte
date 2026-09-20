<script>
import Icon from '@iconify/css-svelte';
import '../../css/g/gytnv0b5e.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="gytnv0b5e"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="mdi:book-search-outline" {...props}></Icon>
