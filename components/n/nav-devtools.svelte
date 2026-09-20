<script>
import Icon from '@iconify/css-svelte';
import '../../css/g/gii8w5ebd.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":16,"height":16};
const content = `<path class="gii8w5ebd"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="oui:nav-devtools" {...props}></Icon>
