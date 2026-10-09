<script>
import Icon from '@iconify/css-svelte';
import '../../css/q/qb5gahbns.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":48,"height":48};
const content = `<path class="qb5gahbns"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="energy-icons:peak-demand-48" {...props}></Icon>
