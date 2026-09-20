<script>
import Icon from '@iconify/css-svelte';
import '../../css/z/zaukvj20g.css';
import '../../css/b/b0-egysls.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="zaukvj20g"/><path class="b0-egysls"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="tdesign:chat-add-filled" {...props}></Icon>
