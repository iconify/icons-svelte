<script>
import Icon from '@iconify/css-svelte';
import '../../css/j/j3yb8ub5l.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path class="j3yb8ub5l"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="selfhst:krakend" {...props}></Icon>
