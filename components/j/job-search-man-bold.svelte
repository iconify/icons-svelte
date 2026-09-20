<script>
import Icon from '@iconify/css-svelte';
import '../../css/k/kmrroccsk.css';
import '../../css/n/n3g_7jbbt.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="kmrroccsk"/><path class="n3g_7jbbt"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="streamline-ultimate:job-search-man-bold" {...props}></Icon>
