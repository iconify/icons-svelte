<script>
import Icon from '@iconify/css-svelte';
import '../../css/d/d2e8wbcsi.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="d2e8wbcsi"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="keyline-icons:eject" {...props}></Icon>
