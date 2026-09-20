<script>
import Icon from '@iconify/css-svelte';
import '../../css/x/xf-0_1bay.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="xf-0_1bay"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="mingcute:brush-2-ai-fill" {...props}></Icon>
