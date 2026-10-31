<script>
import Icon from '@iconify/css-svelte';
import '../../css/d/dtgqigzcn.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="dtgqigzcn"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="coolicons:flame-bulk-round" {...props}></Icon>
