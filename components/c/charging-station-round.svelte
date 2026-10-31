<script>
import Icon from '@iconify/css-svelte';
import '../../css/o/odvfx7z2q.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="odvfx7z2q"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="coolicons:charging-station-round" {...props}></Icon>
