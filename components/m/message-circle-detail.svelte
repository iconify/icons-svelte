<script>
import Icon from '@iconify/css-svelte';
import '../../css/l/l5tcskb1o.css';
import '../../css/f/fu72iwgtz.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="l5tcskb1o"/><path class="fu72iwgtz"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="boxicons:message-circle-detail" {...props}></Icon>
