<script>
import Icon from '@iconify/css-svelte';
import '../../css/j/jd9tt7pmf.css';
import '../../css/u/uv305zbwv.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":48,"height":48};
const content = `<path class="jd9tt7pmf"/><path class="uv305zbwv"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="energy-icons:data-pipeline-48-bold" {...props}></Icon>
