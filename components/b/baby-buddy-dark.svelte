<script>
import Icon from '@iconify/css-svelte';
import '../../css/j/jrlt_pgpy.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path class="jrlt_pgpy"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="selfhst:baby-buddy-dark" {...props}></Icon>
