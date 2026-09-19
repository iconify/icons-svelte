<script>
import Icon from '@iconify/css-svelte';
import '../../css/q/qruyi9g6m.css';
import '../../css/k/k9qv75bnx.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="qruyi9g6m"/><path class="k9qv75bnx"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="boxicons:cookie" {...props}></Icon>
