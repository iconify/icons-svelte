<script>
import Icon from '@iconify/css-svelte';
import '../../css/i/i11dx0b2j.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="i11dx0b2j"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="ri:atom-line" {...props}></Icon>
