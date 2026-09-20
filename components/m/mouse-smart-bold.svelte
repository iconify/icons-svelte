<script>
import Icon from '@iconify/css-svelte';
import '../../css/o/ondu0mjsi.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="ondu0mjsi"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="streamline-ultimate:mouse-smart-bold" {...props}></Icon>
