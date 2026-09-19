<script>
import Icon from '@iconify/css-svelte';
import '../../css/u/u076ouqcu.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":31,"height":24};
const content = `<path class="u076ouqcu"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="fontisto:behance" {...props}></Icon>
