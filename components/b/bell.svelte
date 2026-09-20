<script>
import Icon from '@iconify/css-svelte';
import '../../css/r/rb_bkrocs.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path class="rb_bkrocs"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="subway:bell" {...props}></Icon>
