<script>
import Icon from '@iconify/css-svelte';
import '../../css/p/pd0ibrbxj.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":48,"height":48};
const content = `<path class="pd0ibrbxj"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="energy-icons:crusher-48-bold" {...props}></Icon>
