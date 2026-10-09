<script>
import Icon from '@iconify/css-svelte';
import '../../css/z/ze82bcb9d.css';
import '../../css/s/su1__b-9u.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":48,"height":48};
const content = `<path class="ze82bcb9d"/><path class="su1__b-9u"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="energy-icons:lithium-48" {...props}></Icon>
