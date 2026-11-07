<script>
import Icon from '@iconify/css-svelte';
import '../../css/q/q_d_ntx3z.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="q_d_ntx3z"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="solar:move-vertical-linear" {...props}></Icon>
