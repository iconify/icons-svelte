<script>
import Icon from '@iconify/css-svelte';
import '../../css/z/zvxx9rbxb.css';
import '../../css/i/iz0l5_b0a.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="zvxx9rbxb"/><path clip-rule="evenodd" class="iz0l5_b0a"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="mingcute:gesture-unlock-fill" {...props}></Icon>
