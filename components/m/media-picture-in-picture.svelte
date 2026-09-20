<script>
import Icon from '@iconify/css-svelte';
import '../../css/p/pu-ic6bvo.css';
import '../../css/u/ujklyuwmo.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="pu-ic6bvo"/><path class="ujklyuwmo"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="nrk:media-picture-in-picture" {...props}></Icon>
