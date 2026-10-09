<script>
import Icon from '@iconify/css-svelte';
import '../../css/m/m81sh779s.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":48,"height":48};
const content = `<path class="m81sh779s"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="energy-icons:list-ordered-48" {...props}></Icon>
