<script>
import Icon from '@iconify/css-svelte';
import '../../css/v/v_wzyuc_q.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="v_wzyuc_q"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="hugeicons:chart-01" {...props}></Icon>
