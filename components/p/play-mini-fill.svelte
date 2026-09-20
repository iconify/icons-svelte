<script>
import Icon from '@iconify/css-svelte';
import '../../css/v/vnti9qbac.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="vnti9qbac"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="ri:play-mini-fill" {...props}></Icon>
