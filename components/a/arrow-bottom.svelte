<script>
import Icon from '@iconify/css-svelte';
import '../../css/f/faps_v1gv.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":8,"height":8};
const content = `<path class="faps_v1gv"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="oi:arrow-bottom" {...props}></Icon>
