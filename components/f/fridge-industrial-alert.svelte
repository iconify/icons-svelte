<script>
import Icon from '@iconify/css-svelte';
import '../../css/i/i68cpbcbd.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="i68cpbcbd"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="mdi:fridge-industrial-alert" {...props}></Icon>
