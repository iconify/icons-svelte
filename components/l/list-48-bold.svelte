<script>
import Icon from '@iconify/css-svelte';
import '../../css/h/h-p1p0bqc.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":48,"height":48};
const content = `<path class="h-p1p0bqc"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="energy-icons:list-48-bold" {...props}></Icon>
