<script>
import Icon from '@iconify/css-svelte';
import '../../css/m/m6rbxzurq.css';
import '../../css/v/vvznrfbcw.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="m6rbxzurq"/><path class="vvznrfbcw"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="lucide-extended:mail-dot-filled" {...props}></Icon>
