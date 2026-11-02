<script>
import Icon from '@iconify/css-svelte';
import '../../css/g/g72_w6bzg.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="g72_w6bzg"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="mingcute:rewind-backward-5-fill" {...props}></Icon>
