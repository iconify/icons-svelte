<script>
import Icon from '@iconify/css-svelte';
import '../../css/m/mfr5lhbab.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="mfr5lhbab"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="boxicons:doughnut-chart" {...props}></Icon>
