<script>
import Icon from '@iconify/css-svelte';
import '../../css/b/btun33och.css';
import '../../css/e/evswpnqiu.css';
import '../../css/n/n8xi_5opn.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="btun33och"/><path class="evswpnqiu"/><path class="n8xi_5opn"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="streamline-freehand:conversation-question-text-1" {...props}></Icon>
