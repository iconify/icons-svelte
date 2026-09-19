<script>
import Icon from '@iconify/css-svelte';
import '../../css/n/n1c1sxbsm.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="n1c1sxbsm"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="hugeicons:pill-off" {...props}></Icon>
