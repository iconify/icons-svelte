<script>
import Icon from '@iconify/css-svelte';
import '../../css/d/dhecyob8y.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="dhecyob8y"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="mingcute:quill-pen-ai-line" {...props}></Icon>
