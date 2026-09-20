<script>
import Icon from '@iconify/css-svelte';
import '../../css/l/li5ilbssx.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="li5ilbssx"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="mdi:fridge-variant-off-outline" {...props}></Icon>
