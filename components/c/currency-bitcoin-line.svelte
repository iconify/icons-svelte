<script>
import Icon from '@iconify/css-svelte';
import '../../css/a/amvtn4bof.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="amvtn4bof"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="mingcute:currency-bitcoin-line" {...props}></Icon>
