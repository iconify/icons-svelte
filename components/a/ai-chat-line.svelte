<script>
import Icon from '@iconify/css-svelte';
import '../../css/j/j7fmnlb4r.css';
import '../../css/j/jn2e1oaba.css';
import '../../css/l/lhkps1b5o.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="j7fmnlb4r"><path class="jn2e1oaba"/><path class="lhkps1b5o"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="si:ai-chat-line" {...props}></Icon>
