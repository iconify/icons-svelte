<script>
import Icon from '@iconify/css-svelte';
import '../../css/e/ejdx2fbwp.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":32,"height":32};
const content = `<path class="ejdx2fbwp"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="la:cloud-moon-rain" {...props}></Icon>
