<script>
import Icon from '@iconify/css-svelte';
import '../../css/x/xaxv-gbpo.css';
import '../../css/x/xp00lybfm.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="xaxv-gbpo"/><path class="xp00lybfm"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="bx:bx-right-down-arrow-circle" {...props}></Icon>
