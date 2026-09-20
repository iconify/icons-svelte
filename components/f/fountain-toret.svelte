<script>
import Icon from '@iconify/css-svelte';
import '../../css/d/d5m6s7ndc.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":16,"height":16};
const content = `<path class="d5m6s7ndc"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="roentgen:fountain-toret" {...props}></Icon>
