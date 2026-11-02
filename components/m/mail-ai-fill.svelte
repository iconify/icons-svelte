<script>
import Icon from '@iconify/css-svelte';
import '../../css/k/klw64wbtg.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="klw64wbtg"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="mingcute:mail-ai-fill" {...props}></Icon>
