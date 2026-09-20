<script>
import Icon from '@iconify/css-svelte';
import '../../css/k/k_i17xbai.css';
import '../../css/l/llov8mbku.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="k_i17xbai"/><path class="llov8mbku"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="tdesign:ai-terminal-filled" {...props}></Icon>
