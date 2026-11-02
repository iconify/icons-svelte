<script>
import Icon from '@iconify/css-svelte';
import '../../css/d/dl49655mb.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="dl49655mb"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="mingcute:fish-off-fill" {...props}></Icon>
