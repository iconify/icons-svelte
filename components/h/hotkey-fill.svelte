<script>
import Icon from '@iconify/css-svelte';
import '../../css/c/cyez6_ixh.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="cyez6_ixh"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="mingcute:hotkey-fill" {...props}></Icon>
