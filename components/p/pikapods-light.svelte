<script>
import Icon from '@iconify/css-svelte';
import '../../css/j/jxz3zon3q.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path class="jxz3zon3q"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="selfhst:pikapods-light" {...props}></Icon>
