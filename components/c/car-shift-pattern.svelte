<script>
import Icon from '@iconify/css-svelte';
import '../../css/e/eti55krty.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="eti55krty"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="mdi:car-shift-pattern" {...props}></Icon>
