<script>
import Icon from '@iconify/css-svelte';
import '../../css/c/ck_0vwbgo.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="ck_0vwbgo"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="hugeicons:rotate-top-right" {...props}></Icon>
