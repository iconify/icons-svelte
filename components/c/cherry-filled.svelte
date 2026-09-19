<script>
import Icon from '@iconify/css-svelte';
import '../../css/s/se4_yi4nq.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="se4_yi4nq"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="boxicons:cherry-filled" {...props}></Icon>
