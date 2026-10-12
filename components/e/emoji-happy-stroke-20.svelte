<script>
import Icon from '@iconify/css-svelte';
import '../../css/q/qujl5dbry.css';
import '../../css/y/yynfaacui.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":20,"height":20};
const content = `<path class="qujl5dbry"/><path class="yynfaacui"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="garden:emoji-happy-stroke-20" {...props}></Icon>
