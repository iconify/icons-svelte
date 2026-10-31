<script>
import Icon from '@iconify/css-svelte';
import '../../css/t/t3s_anb0b.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="t3s_anb0b"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="coolicons:fold-vertical-fill-round" {...props}></Icon>
