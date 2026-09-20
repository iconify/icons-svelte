<script>
import Icon from '@iconify/css-svelte';
import '../../css/e/ecwn0mb8b.css';
import '../../css/b/beq9-lbqg.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="ecwn0mb8b"/><path class="beq9-lbqg"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="tdesign:chat-bubble-locked-filled" {...props}></Icon>
