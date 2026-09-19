<script>
import Icon from '@iconify/css-svelte';
import '../../css/w/w1her1mbe.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="w1her1mbe"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="bx:bxs-message-add" {...props}></Icon>
