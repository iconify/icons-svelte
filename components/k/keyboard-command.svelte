<script>
import Icon from '@iconify/css-svelte';
import '../../css/n/nctidhb8j.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="nctidhb8j"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="proicons:keyboard-command" {...props}></Icon>
