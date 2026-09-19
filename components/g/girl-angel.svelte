<script>
import Icon from '@iconify/css-svelte';
import '../../css/b/bqlv_3b2t.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path class="bqlv_3b2t"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="ps:girl-angel" {...props}></Icon>
