<script>
import Icon from '@iconify/css-svelte';
import '../../css/x/xudp2625p.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":1024,"height":1024};
const content = `<path class="xudp2625p"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="whh:circlee" {...props}></Icon>
