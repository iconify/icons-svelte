<script>
import Icon from '@iconify/css-svelte';
import '../../css/l/l8w5gd35u.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="l8w5gd35u"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="hugeicons:ai-content-generator-01" {...props}></Icon>
