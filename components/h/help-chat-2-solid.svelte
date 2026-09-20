<script>
import Icon from '@iconify/css-svelte';
import '../../css/t/td4tfzdnw.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":14,"height":14};
const content = `<path clip-rule="evenodd" class="td4tfzdnw"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="streamline:help-chat-2-solid" {...props}></Icon>
