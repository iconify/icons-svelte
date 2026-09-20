<script>
import Icon from '@iconify/css-svelte';
import '../../css/c/c2umwkbls.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="c2umwkbls"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="lucide:bar-chart-4" {...props}></Icon>
