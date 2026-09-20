<script>
import Icon from '@iconify/css-svelte';
import '../../css/c/c_is6obug.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="c_is6obug"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="mdi:email-search-outline" {...props}></Icon>
