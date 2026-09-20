<script>
import Icon from '@iconify/css-svelte';
import '../../css/m/mmf2iu29k.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":16,"height":16};
const content = `<path clip-rule="evenodd" class="mmf2iu29k"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="lsicon:order-filled" {...props}></Icon>
