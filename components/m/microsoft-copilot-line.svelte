<script>
import Icon from '@iconify/css-svelte';
import '../../css/x/xa_16ujdz.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="xa_16ujdz"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="ri:microsoft-copilot-line" {...props}></Icon>
