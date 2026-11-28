<script>
import Icon from '@iconify/css-svelte';
import '../../css/k/kuq6snofp.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="kuq6snofp"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="noviair-light:music-heart" {...props}></Icon>
