<script>
import Icon from '@iconify/css-svelte';
import '../../css/b/bza6e2esc.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path class="bza6e2esc"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="fa6-regular:rectangle-xmark" {...props}></Icon>
