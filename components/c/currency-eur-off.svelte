<script>
import Icon from '@iconify/css-svelte';
import '../../css/z/z2b0_2bec.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="z2b0_2bec"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="mdi:currency-eur-off" {...props}></Icon>
