<script>
import Icon from '@iconify/css-svelte';
import '../../css/l/l4q2x981q.css';
import '../../css/x/xg4x14bqu.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="l4q2x981q"/><path class="xg4x14bqu"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="uim:arrow-down-right" {...props}></Icon>
