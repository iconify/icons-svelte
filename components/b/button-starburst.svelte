<script>
import Icon from '@iconify/css-svelte';
import '../../css/s/szv6o4bks.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":17,"height":16};
const content = `<path class="szv6o4bks"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="si-glyph:button-starburst" {...props}></Icon>
