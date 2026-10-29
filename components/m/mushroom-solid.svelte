<script>
import Icon from '@iconify/css-svelte';
import '../../css/d/d8zd_tzji.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="d8zd_tzji"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="withicons:mushroom-solid" {...props}></Icon>
