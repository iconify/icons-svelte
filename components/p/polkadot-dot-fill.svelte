<script>
import Icon from '@iconify/css-svelte';
import '../../css/d/dvvtsgrrx.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="dvvtsgrrx"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="mingcute:polkadot-dot-fill" {...props}></Icon>
