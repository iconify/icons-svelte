<script>
import Icon from '@iconify/css-svelte';
import '../../css/a/aqsf4sb_k.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="aqsf4sb_k"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="boxicons:backpack" {...props}></Icon>
