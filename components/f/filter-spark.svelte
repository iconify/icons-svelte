<script>
import Icon from '@iconify/css-svelte';
import '../../css/d/d59_tovyd.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="d59_tovyd"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="tabler:filter-spark" {...props}></Icon>
