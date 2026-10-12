<script>
import Icon from '@iconify/css-svelte';
import '../../css/a/ai-ap6q9e.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="ai-ap6q9e"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="lucide-extended:cat-filled" {...props}></Icon>
