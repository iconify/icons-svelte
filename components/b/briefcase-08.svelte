<script>
import Icon from '@iconify/css-svelte';
import '../../css/l/ljocc-b3w.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="ljocc-b3w"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="hugeicons:briefcase-08" {...props}></Icon>
