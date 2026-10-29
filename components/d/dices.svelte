<script>
import Icon from '@iconify/css-svelte';
import '../../css/n/nupinubwa.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="nupinubwa"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="vadivam:dices" {...props}></Icon>
