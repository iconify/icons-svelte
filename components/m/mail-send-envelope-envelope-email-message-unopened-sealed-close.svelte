<script>
import Icon from '@iconify/css-svelte';
import '../../css/y/y9tr6bcfx.css';
import '../../css/c/c975v6b7u.css';
import '../../css/o/ov7637cjy.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":14,"height":14};
const content = `<g class="y9tr6bcfx"><rect class="c975v6b7u"/><path class="ov7637cjy"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="streamline:mail-send-envelope-envelope-email-message-unopened-sealed-close" {...props}></Icon>
