<script>
import Icon from '@iconify/css-svelte';
import '../../css/y/y3i123b1r.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="y3i123b1r"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="tabler:glass-full-filled" {...props}></Icon>
