<script>
import Icon from '@iconify/css-svelte';
import '../../css/e/e61cy3bkq.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="e61cy3bkq"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="mdi:energy-to-grid" {...props}></Icon>
