<script>
import Icon from '@iconify/css-svelte';
import '../../css/t/tgg-4hbjn.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="tgg-4hbjn"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="mdi:house-city" {...props}></Icon>
