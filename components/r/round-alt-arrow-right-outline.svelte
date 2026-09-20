<script>
import Icon from '@iconify/css-svelte';
import '../../css/v/vvwsdn9ho.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="vvwsdn9ho"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="solar:round-alt-arrow-right-outline" {...props}></Icon>
