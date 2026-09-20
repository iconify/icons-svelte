<script>
import Icon from '@iconify/css-svelte';
import '../../css/u/uoi-wib1s.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="uoi-wib1s"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="mage:dashboard-chart-fill" {...props}></Icon>
