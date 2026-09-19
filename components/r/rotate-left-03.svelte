<script>
import Icon from '@iconify/css-svelte';
import '../../css/d/d6-p95b7h.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="d6-p95b7h"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="hugeicons:rotate-left-03" {...props}></Icon>
