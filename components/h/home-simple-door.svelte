<script>
import Icon from '@iconify/css-svelte';
import '../../css/i/ie-yfem4r.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="ie-yfem4r"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="iconoir:home-simple-door" {...props}></Icon>
