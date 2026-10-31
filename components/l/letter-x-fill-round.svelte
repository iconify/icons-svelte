<script>
import Icon from '@iconify/css-svelte';
import '../../css/u/umpfuubtt.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="umpfuubtt"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="coolicons:letter-x-fill-round" {...props}></Icon>
