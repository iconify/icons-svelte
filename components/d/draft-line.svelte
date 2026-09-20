<script>
import Icon from '@iconify/css-svelte';
import '../../css/v/vy6bvdbas.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="vy6bvdbas"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="ri:draft-line" {...props}></Icon>
