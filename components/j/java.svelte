<script>
import Icon from '@iconify/css-svelte';
import '../../css/r/rrvu35b3m.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":8,"height":8};
const content = `<path class="rrvu35b3m"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="picon:java" {...props}></Icon>
