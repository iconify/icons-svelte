<script>
import Icon from '@iconify/css-svelte';
import '../../css/u/uh2t47oxp.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="uh2t47oxp"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="bx:bxs-message-square-minus" {...props}></Icon>
