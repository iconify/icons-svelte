<script>
import Icon from '@iconify/css-svelte';
import '../../css/l/lm33rhd9w.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="lm33rhd9w"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="ri:mv-ai-fill" {...props}></Icon>
