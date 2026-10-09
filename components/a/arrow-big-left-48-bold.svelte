<script>
import Icon from '@iconify/css-svelte';
import '../../css/n/n4coe1bze.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":48,"height":48};
const content = `<path class="n4coe1bze"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="energy-icons:arrow-big-left-48-bold" {...props}></Icon>
