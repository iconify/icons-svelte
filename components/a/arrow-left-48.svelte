<script>
import Icon from '@iconify/css-svelte';
import '../../css/x/x9t00gb6u.css';
import '../../css/u/ujj6t-i1r.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":48,"height":48};
const content = `<path class="x9t00gb6u"/><path class="ujj6t-i1r"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="energy-icons:arrow-left-48" {...props}></Icon>
