<script>
import Icon from '@iconify/css-svelte';
import '../../css/d/d4mjjratt.css';
import '../../css/d/d45xejkbu.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":20,"height":20};
const content = `<path class="d4mjjratt"/><path class="d45xejkbu"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="energy-icons:align-bottom-20-bold" {...props}></Icon>
