<script>
import Icon from '@iconify/css-svelte';
import '../../css/p/pfon71bpq.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":1200,"height":1200};
const content = `<path class="pfon71bpq"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="el:phone" {...props}></Icon>
