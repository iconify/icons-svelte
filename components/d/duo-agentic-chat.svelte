<script>
import Icon from '@iconify/css-svelte';
import '../../css/p/pc8ang44w.css';
import '../../css/e/eh-2z7b3c.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":16,"height":16};
const content = `<path class="pc8ang44w"/><path class="eh-2z7b3c"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="pajamas:duo-agentic-chat" {...props}></Icon>
