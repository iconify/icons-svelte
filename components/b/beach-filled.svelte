<script>
import Icon from '@iconify/css-svelte';
import '../../css/v/v7c0-q0sw.css';
import '../../css/s/sgg5g4blt.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="v7c0-q0sw"/><path class="sgg5g4blt"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="boxicons:beach-filled" {...props}></Icon>
