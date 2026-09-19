<script>
import Icon from '@iconify/css-svelte';
import '../../css/v/vnnwubjuz.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="vnnwubjuz"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="bx:bx-pound" {...props}></Icon>
