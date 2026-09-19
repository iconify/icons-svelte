<script>
import Icon from '@iconify/css-svelte';
import '../../css/x/xgrm3qbet.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="xgrm3qbet"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="bx:bxs-landmark" {...props}></Icon>
