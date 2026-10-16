<script>
import Icon from '@iconify/css-svelte';
import '../../css/p/pb7h-ubmy.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":48,"height":48};
const content = `<path class="pb7h-ubmy"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="energy-icons:chart-funnel-48" {...props}></Icon>
