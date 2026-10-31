<script>
import Icon from '@iconify/css-svelte';
import '../../css/l/lp11kbk4z.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="lp11kbk4z"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="coolicons:mail-sparkle-fill-round" {...props}></Icon>
