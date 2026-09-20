<script>
import Icon from '@iconify/css-svelte';
import '../../css/z/z4x25obrb.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="z4x25obrb"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="token:binance" {...props}></Icon>
