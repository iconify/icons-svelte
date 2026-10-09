<script>
import Icon from '@iconify/css-svelte';
import '../../css/x/x6bo5g7fy.css';
import '../../css/p/p0blm-arr.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":48,"height":48};
const content = `<path class="x6bo5g7fy"/><path class="p0blm-arr"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="energy-icons:jar-48" {...props}></Icon>
