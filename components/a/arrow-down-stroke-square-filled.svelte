<script>
import Icon from '@iconify/css-svelte';
import '../../css/x/x2avr2bzb.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="x2avr2bzb"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="boxicons:arrow-down-stroke-square-filled" {...props}></Icon>
