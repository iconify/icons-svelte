<script>
import Icon from '@iconify/css-svelte';
import '../../css/o/oc237m_zh.css';
import '../../css/i/i_kfg6brk.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":48,"height":48};
const content = `<path class="oc237m_zh"/><path class="i_kfg6brk"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="streamline-emojis:paperclip" {...props}></Icon>
