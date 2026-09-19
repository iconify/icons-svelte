<script>
import Icon from '@iconify/css-svelte';
import '../../css/q/qbmlz2beh.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="qbmlz2beh"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="healthicons:chart-cured-decreasing-24px" {...props}></Icon>
