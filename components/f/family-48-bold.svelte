<script>
import Icon from '@iconify/css-svelte';
import '../../css/e/e8nquq1lm.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":48,"height":48};
const content = `<path class="e8nquq1lm"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="energy-icons:family-48-bold" {...props}></Icon>
