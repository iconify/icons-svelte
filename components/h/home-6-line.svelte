<script>
import Icon from '@iconify/css-svelte';
import '../../css/a/amm1rn32k.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="amm1rn32k"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="mingcute:home-6-line" {...props}></Icon>
