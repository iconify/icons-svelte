<script>
import Icon from '@iconify/css-svelte';
import '../../css/c/c9_on4g5x.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":48,"height":48};
const content = `<path class="c9_on4g5x"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="energy-icons:activity-48-bold" {...props}></Icon>
