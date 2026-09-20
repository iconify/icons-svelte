<script>
import Icon from '@iconify/css-svelte';
import '../../css/e/eh57mdb9w.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":32,"height":32};
const content = `<path class="eh57mdb9w"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="streamline-pixel:map-navigation-compass-direction" {...props}></Icon>
