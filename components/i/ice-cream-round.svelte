<script>
import Icon from '@iconify/css-svelte';
import '../../css/k/kia26mbgm.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="kia26mbgm"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="coolicons:ice-cream-round" {...props}></Icon>
