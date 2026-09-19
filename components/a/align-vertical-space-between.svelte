<script>
import Icon from '@iconify/css-svelte';
import '../../css/d/d58_ggb7r.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="d58_ggb7r"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="boxicons:align-vertical-space-between" {...props}></Icon>
