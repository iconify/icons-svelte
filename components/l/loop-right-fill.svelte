<script>
import Icon from '@iconify/css-svelte';
import '../../css/p/p-6h55buz.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="p-6h55buz"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="ri:loop-right-fill" {...props}></Icon>
