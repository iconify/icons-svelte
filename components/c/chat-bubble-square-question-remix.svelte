<script>
import Icon from '@iconify/css-svelte';
import '../../css/h/h84gtiblq.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":48,"height":48};
const content = `<path clip-rule="evenodd" class="h84gtiblq"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="streamline-plump:chat-bubble-square-question-remix" {...props}></Icon>
