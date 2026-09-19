<script>
import Icon from '@iconify/css-svelte';
import '../../css/u/unkafc4eq.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="unkafc4eq"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="hugeicons:chart-column" {...props}></Icon>
