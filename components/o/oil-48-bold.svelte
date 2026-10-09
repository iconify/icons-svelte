<script>
import Icon from '@iconify/css-svelte';
import '../../css/j/jpu4n9bbu.css';
import '../../css/r/r5moseb1w.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":48,"height":48};
const content = `<path class="jpu4n9bbu"/><path class="r5moseb1w"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="energy-icons:oil-48-bold" {...props}></Icon>
