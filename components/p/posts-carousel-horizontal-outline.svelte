<script>
import Icon from '@iconify/css-svelte';
import '../../css/s/s1jmd4bmi.css';
import '../../css/h/haze59b4w.css';
import '../../css/z/zyijgil5y.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="s1jmd4bmi"/><path class="haze59b4w"/><path class="zyijgil5y"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="solar:posts-carousel-horizontal-outline" {...props}></Icon>
