<script>
import Icon from '@iconify/css-svelte';
import '../../css/s/ss0igbcet.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":48,"height":48};
const content = `<path class="ss0igbcet"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="energy-icons:hail-48-bold" {...props}></Icon>
