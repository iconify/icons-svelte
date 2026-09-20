<script>
import Icon from '@iconify/css-svelte';
import '../../css/u/uff_9unyb.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="uff_9unyb"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="ri:number-1" {...props}></Icon>
