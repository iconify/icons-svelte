<script>
import Icon from '@iconify/css-svelte';
import '../../css/g/g2r0g7b4b.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":48,"height":48};
const content = `<path class="g2r0g7b4b"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="energy-icons:energy-mix-48-bold" {...props}></Icon>
