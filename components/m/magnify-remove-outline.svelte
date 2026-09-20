<script>
import Icon from '@iconify/css-svelte';
import '../../css/f/f5rd1n78g.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="f5rd1n78g"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="mdi:magnify-remove-outline" {...props}></Icon>
