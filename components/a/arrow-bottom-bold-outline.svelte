<script>
import Icon from '@iconify/css-svelte';
import '../../css/u/u-x-zabat.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="u-x-zabat"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="mdi:arrow-bottom-bold-outline" {...props}></Icon>
