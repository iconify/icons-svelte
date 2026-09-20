<script>
import Icon from '@iconify/css-svelte';
import '../../css/x/x93dmqdrl.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="x93dmqdrl"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="lineicons:board-writing-3" {...props}></Icon>
