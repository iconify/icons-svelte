<script>
import Icon from '@iconify/css-svelte';
import '../../css/k/k_g2f6aqs.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":48,"height":48};
const content = `<path class="k_g2f6aqs"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="energy-icons:line-fault-48" {...props}></Icon>
