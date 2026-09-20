<script>
import Icon from '@iconify/css-svelte';
import '../../css/b/b6q1_pb0m.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="b6q1_pb0m"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="mingcute:edit-3-ai-fill" {...props}></Icon>
