<script>
import Icon from '@iconify/css-svelte';
import '../../css/k/kmq8itb1q.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="kmq8itb1q"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="hugeicons:briefcase-08" {...props}></Icon>
