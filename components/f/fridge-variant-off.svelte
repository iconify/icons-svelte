<script>
import Icon from '@iconify/css-svelte';
import '../../css/o/o-_p4h7pk.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="o-_p4h7pk"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="mdi:fridge-variant-off" {...props}></Icon>
