<script>
import Icon from '@iconify/css-svelte';
import '../../css/b/b2ipv8b3q.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path class="b2ipv8b3q"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="selfhst:daylog-dark" {...props}></Icon>
