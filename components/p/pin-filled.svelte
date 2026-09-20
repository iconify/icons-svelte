<script>
import Icon from '@iconify/css-svelte';
import '../../css/x/xluo-0b2x.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":16,"height":16};
const content = `<path clip-rule="evenodd" class="xluo-0b2x"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="lsicon:pin-filled" {...props}></Icon>
