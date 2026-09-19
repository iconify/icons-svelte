<script>
import Icon from '@iconify/css-svelte';
import '../../css/j/jph6_ql_q.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="jph6_ql_q"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="hugeicons:drill" {...props}></Icon>
