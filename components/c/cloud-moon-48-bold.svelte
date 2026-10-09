<script>
import Icon from '@iconify/css-svelte';
import '../../css/h/hwy0au9lc.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":48,"height":48};
const content = `<path class="hwy0au9lc"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="energy-icons:cloud-moon-48-bold" {...props}></Icon>
