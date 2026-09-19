<script>
import Icon from '@iconify/css-svelte';
import '../../css/e/e05gnybdo.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="e05gnybdo"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="hugeicons:pause" {...props}></Icon>
