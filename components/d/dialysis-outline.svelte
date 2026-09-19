<script>
import Icon from '@iconify/css-svelte';
import '../../css/i/iwza8kbcl.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":48,"height":48};
const content = `<path class="iwza8kbcl"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="healthicons:dialysis-outline" {...props}></Icon>
