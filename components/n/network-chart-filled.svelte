<script>
import Icon from '@iconify/css-svelte';
import '../../css/b/bnlv51ewt.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="bnlv51ewt"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="boxicons:network-chart-filled" {...props}></Icon>
