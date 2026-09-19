<script>
import Icon from '@iconify/css-svelte';
import '../../css/l/lzi65lbfq.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":432,"height":432};
const content = `<path class="lzi65lbfq"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="zmdi:email-open" {...props}></Icon>
