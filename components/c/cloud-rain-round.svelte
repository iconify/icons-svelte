<script>
import Icon from '@iconify/css-svelte';
import '../../css/t/twa787xup.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="twa787xup"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="coolicons:cloud-rain-round" {...props}></Icon>
