<script>
import Icon from '@iconify/css-svelte';
import '../../css/x/xxqw9b-rt.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":48,"height":48};
const content = `<path class="xxqw9b-rt"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="energy-icons:floating-solar-48-bold" {...props}></Icon>
