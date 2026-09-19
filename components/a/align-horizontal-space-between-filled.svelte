<script>
import Icon from '@iconify/css-svelte';
import '../../css/n/n8o2mmbrq.css';
import '../../css/t/t_9pnl1bo.css';
import '../../css/z/zvvso5rkk.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="n8o2mmbrq"/><rect class="t_9pnl1bo"/><rect class="zvvso5rkk"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="boxicons:align-horizontal-space-between-filled" {...props}></Icon>
