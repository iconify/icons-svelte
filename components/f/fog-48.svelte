<script>
import Icon from '@iconify/css-svelte';
import '../../css/g/g9nqk8bld.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":48,"height":48};
const content = `<path class="g9nqk8bld"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="energy-icons:fog-48" {...props}></Icon>
