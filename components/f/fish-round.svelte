<script>
import Icon from '@iconify/css-svelte';
import '../../css/v/vfvj6mbph.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="vfvj6mbph"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="coolicons:fish-round" {...props}></Icon>
