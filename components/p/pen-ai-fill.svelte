<script>
import Icon from '@iconify/css-svelte';
import '../../css/l/lkl9mhbcs.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="lkl9mhbcs"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="mingcute:pen-ai-fill" {...props}></Icon>
