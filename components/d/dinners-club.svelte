<script>
import Icon from '@iconify/css-svelte';
import '../../css/r/ri5yisb4w.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":36,"height":24};
const content = `<path class="ri5yisb4w"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="fontisto:dinners-club" {...props}></Icon>
