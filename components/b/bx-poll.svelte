<script>
import Icon from '@iconify/css-svelte';
import '../../css/a/ahr1-k04q.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="ahr1-k04q"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="bx:bx-poll" {...props}></Icon>
