<script>
import Icon from '@iconify/css-svelte';
import '../../css/y/ye8y2k9kx.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="ye8y2k9kx"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="hugeicons:ai-content-generator-01" {...props}></Icon>
