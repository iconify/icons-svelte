<script>
import Icon from '@iconify/css-svelte';
import '../../css/t/trq-q2bnu.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="trq-q2bnu"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="boxicons:network-chart" {...props}></Icon>
