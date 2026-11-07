<script>
import Icon from '@iconify/css-svelte';
import '../../css/v/vipk1m54q.css';
import '../../css/l/lbzbb7bkq.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="vipk1m54q"/><path class="lbzbb7bkq"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="solar:oven-mitts-bold" {...props}></Icon>
