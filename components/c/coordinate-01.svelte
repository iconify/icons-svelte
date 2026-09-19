<script>
import Icon from '@iconify/css-svelte';
import '../../css/f/f-bshlbmr.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="f-bshlbmr"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="hugeicons:coordinate-01" {...props}></Icon>
