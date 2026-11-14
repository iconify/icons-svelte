<script>
import Icon from '@iconify/css-svelte';
import '../../css/j/jx0p4fbya.css';
import '../../css/f/fdha4crhi.css';
import '../../css/k/kcz4c0b0u.css';
import '../../css/x/xqkz5x74a.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="jx0p4fbya"><path class="fdha4crhi"/><path class="kcz4c0b0u"/><path class="xqkz5x74a"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="hugeicons:message-notification-02" {...props}></Icon>
