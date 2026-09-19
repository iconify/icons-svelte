<script>
import Icon from '@iconify/css-svelte';
import '../../css/l/l25j-x-4p.css';
import '../../css/z/z-9vsgwta.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="l25j-x-4p"/><path class="z-9vsgwta"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="bx:bxs-backpack" {...props}></Icon>
