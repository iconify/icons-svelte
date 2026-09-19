<script>
import Icon from '@iconify/css-svelte';
import '../../css/d/d7ubd6bti.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="d7ubd6bti"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="hugeicons:rotate-square" {...props}></Icon>
