<script>
import Icon from '@iconify/css-svelte';
import '../../css/e/eb_hvfbgh.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="eb_hvfbgh"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="keyline-icons:cursor-duotone" {...props}></Icon>
