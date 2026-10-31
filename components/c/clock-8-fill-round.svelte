<script>
import Icon from '@iconify/css-svelte';
import '../../css/p/pxkkocc_d.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="pxkkocc_d"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="coolicons:clock-8-fill-round" {...props}></Icon>
