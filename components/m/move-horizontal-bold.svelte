<script>
import Icon from '@iconify/css-svelte';
import '../../css/b/bottp98ly.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="bottp98ly"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="solar:move-horizontal-bold" {...props}></Icon>
