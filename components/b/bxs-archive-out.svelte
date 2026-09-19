<script>
import Icon from '@iconify/css-svelte';
import '../../css/x/x2ruwuqtc.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="x2ruwuqtc"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="bx:bxs-archive-out" {...props}></Icon>
