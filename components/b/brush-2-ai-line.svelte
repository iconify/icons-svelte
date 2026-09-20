<script>
import Icon from '@iconify/css-svelte';
import '../../css/q/q21vddbnm.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="q21vddbnm"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="mingcute:brush-2-ai-line" {...props}></Icon>
