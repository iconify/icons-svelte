<script>
import Icon from '@iconify/css-svelte';
import '../../css/l/le9v28bsd.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="le9v28bsd"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="hugeicons:briefcase-conveyor-belt" {...props}></Icon>
