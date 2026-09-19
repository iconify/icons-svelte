<script>
import Icon from '@iconify/css-svelte';
import '../../css/p/pi90yubzc.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="pi90yubzc"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="hugeicons:chevrons-down" {...props}></Icon>
