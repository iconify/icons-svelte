<script>
import Icon from '@iconify/css-svelte';
import '../../css/s/st62hbcbr.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path class="st62hbcbr"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="subway:down" {...props}></Icon>
