<script>
import Icon from '@iconify/css-svelte';
import '../../css/s/sqkj8vciz.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="sqkj8vciz"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="mdi:bookmark-tick" {...props}></Icon>
