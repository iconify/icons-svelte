<script>
import Icon from '@iconify/css-svelte';
import '../../css/e/eq17i1_qo.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":48,"height":48};
const content = `<path clip-rule="evenodd" class="eq17i1_qo"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="streamline-plump:reply-to-message-typing-remix" {...props}></Icon>
