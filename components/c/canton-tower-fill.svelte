<script>
import Icon from '@iconify/css-svelte';
import '../../css/c/cmdy_eblg.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="cmdy_eblg"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="mingcute:canton-tower-fill" {...props}></Icon>
