<script>
import Icon from '@iconify/css-svelte';
import '../../css/e/e3xuwrd7x.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="e3xuwrd7x"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="mage:dashboard-circle-chart-fill" {...props}></Icon>
