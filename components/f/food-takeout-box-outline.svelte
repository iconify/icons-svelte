<script>
import Icon from '@iconify/css-svelte';
import '../../css/y/y00yb5b9o.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="y00yb5b9o"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="mdi:food-takeout-box-outline" {...props}></Icon>
