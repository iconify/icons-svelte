<script>
import Icon from '@iconify/css-svelte';
import '../../css/y/ym2po6bfu.css';
import '../../css/g/g_ffjxz3n.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="ym2po6bfu"/><path class="g_ffjxz3n"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="tdesign:chat-setting-filled" {...props}></Icon>
