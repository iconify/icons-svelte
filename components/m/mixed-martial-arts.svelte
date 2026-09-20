<script>
import Icon from '@iconify/css-svelte';
import '../../css/n/ndny7ndpc.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="ndny7ndpc"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="mdi:mixed-martial-arts" {...props}></Icon>
