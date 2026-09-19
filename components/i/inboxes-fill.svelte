<script>
import Icon from '@iconify/css-svelte';
import '../../css/f/fp_oi_--r.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":16,"height":16};
const content = `<path class="fp_oi_--r"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="bi:inboxes-fill" {...props}></Icon>
