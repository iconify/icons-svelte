<script>
import Icon from '@iconify/css-svelte';
import '../../css/e/ekry0bbzo.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="ekry0bbzo"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="hugeicons:flashlight-off" {...props}></Icon>
