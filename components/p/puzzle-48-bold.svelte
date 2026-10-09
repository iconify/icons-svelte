<script>
import Icon from '@iconify/css-svelte';
import '../../css/m/ml8ltyb0y.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":48,"height":48};
const content = `<path class="ml8ltyb0y"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="energy-icons:puzzle-48-bold" {...props}></Icon>
