<script>
import Icon from '@iconify/css-svelte';
import '../../css/j/jd34y1bdj.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path class="jd34y1bdj"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="selfhst:daylog-dark" {...props}></Icon>
