<script>
import Icon from '@iconify/css-svelte';
import '../../css/b/bes95g4qn.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="bes95g4qn"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="mingcute:edit-2-ai-fill" {...props}></Icon>
