<script>
import Icon from '@iconify/css-svelte';
import '../../css/m/m7my3gbjh.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="m7my3gbjh"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="withicons:arrow-down-right-solid" {...props}></Icon>
