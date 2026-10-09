<script>
import Icon from '@iconify/css-svelte';
import '../../css/q/qm-zvw_lm.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":48,"height":48};
const content = `<path class="qm-zvw_lm"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="energy-icons:puzzle-48" {...props}></Icon>
