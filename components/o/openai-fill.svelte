<script>
import Icon from '@iconify/css-svelte';
import '../../css/w/wm344n_sz.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="wm344n_sz"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="mingcute:openai-fill" {...props}></Icon>
