<script>
import Icon from '@iconify/css-svelte';
import '../../css/j/jqe6l8ger.css';
import '../../css/v/vzdt97b6q.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":48,"height":48};
const content = `<path class="jqe6l8ger"/><path class="vzdt97b6q"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="energy-icons:corner-right-down-48-bold" {...props}></Icon>
