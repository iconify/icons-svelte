<script>
import Icon from '@iconify/css-svelte';
import '../../css/m/mbth5776q.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="mbth5776q"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="hugeicons:arrow-down-narrow-wide" {...props}></Icon>
