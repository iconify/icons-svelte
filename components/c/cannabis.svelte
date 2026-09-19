<script>
import Icon from '@iconify/css-svelte';
import '../../css/u/uqjf0ebnh.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":48,"height":48};
const content = `<path class="uqjf0ebnh"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="healthicons:cannabis" {...props}></Icon>
