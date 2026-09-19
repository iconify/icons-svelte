<script>
import Icon from '@iconify/css-svelte';
import '../../css/e/e-6lat49e.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="e-6lat49e"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="bx:bxs-briefcase-alt-2" {...props}></Icon>
