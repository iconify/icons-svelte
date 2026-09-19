<script>
import Icon from '@iconify/css-svelte';
import '../../css/j/jxq40_bto.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="jxq40_bto"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="boxicons:clock-5-filled" {...props}></Icon>
