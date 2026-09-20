<script>
import Icon from '@iconify/css-svelte';
import '../../css/m/mt11htw0q.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":8,"height":8};
const content = `<path class="mt11htw0q"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="picon:messenger" {...props}></Icon>
