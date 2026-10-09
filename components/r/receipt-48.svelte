<script>
import Icon from '@iconify/css-svelte';
import '../../css/o/oegrs6bql.css';
import '../../css/o/okiekq7yz.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":48,"height":48};
const content = `<path class="oegrs6bql"/><path class="okiekq7yz"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="energy-icons:receipt-48" {...props}></Icon>
