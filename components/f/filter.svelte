<script>
import Icon from '@iconify/css-svelte';
import '../../css/b/b8xmr5jbq.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":32,"height":32};
const content = `<path class="b8xmr5jbq"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="bytesize:filter" {...props}></Icon>
