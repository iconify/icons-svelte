<script>
import Icon from '@iconify/css-svelte';
import '../../css/v/vkz-oab5u.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="vkz-oab5u"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="withicons:refrigerator-gloss" {...props}></Icon>
