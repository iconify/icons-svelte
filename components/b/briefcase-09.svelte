<script>
import Icon from '@iconify/css-svelte';
import '../../css/s/s78duf93g.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="s78duf93g"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="hugeicons:briefcase-09" {...props}></Icon>
