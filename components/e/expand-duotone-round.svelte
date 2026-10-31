<script>
import Icon from '@iconify/css-svelte';
import '../../css/i/i74gyzbdn.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="i74gyzbdn"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="coolicons:expand-duotone-round" {...props}></Icon>
