<script>
import Icon from '@iconify/css-svelte';
import '../../css/z/zuez5acdz.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="zuez5acdz"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="mingcute:file-ai-fill" {...props}></Icon>
