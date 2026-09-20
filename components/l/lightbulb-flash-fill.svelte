<script>
import Icon from '@iconify/css-svelte';
import '../../css/s/sc5s19shd.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="sc5s19shd"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="ri:lightbulb-flash-fill" {...props}></Icon>
