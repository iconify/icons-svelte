<script>
import Icon from '@iconify/css-svelte';
import '../../css/p/p56h_bbeb.css';
import '../../css/y/yyi__d53g.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="p56h_bbeb"/><path class="yyi__d53g"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="boxicons:message-captions" {...props}></Icon>
