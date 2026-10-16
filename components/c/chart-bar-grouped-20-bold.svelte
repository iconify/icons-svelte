<script>
import Icon from '@iconify/css-svelte';
import '../../css/d/d4mjjratt.css';
import '../../css/f/fnu7wqbon.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":20,"height":20};
const content = `<path class="d4mjjratt"/><path class="fnu7wqbon"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="energy-icons:chart-bar-grouped-20-bold" {...props}></Icon>
