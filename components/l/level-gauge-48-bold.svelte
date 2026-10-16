<script>
import Icon from '@iconify/css-svelte';
import '../../css/v/v9ilzsbir.css';
import '../../css/y/y2aittblo.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":48,"height":48};
const content = `<path class="v9ilzsbir"/><path class="y2aittblo"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="energy-icons:level-gauge-48-bold" {...props}></Icon>
