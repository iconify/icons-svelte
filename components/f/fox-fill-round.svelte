<script>
import Icon from '@iconify/css-svelte';
import '../../css/x/xjp6pgx3h.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="xjp6pgx3h"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="coolicons:fox-fill-round" {...props}></Icon>
