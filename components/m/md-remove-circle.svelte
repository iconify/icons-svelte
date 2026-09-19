<script>
import Icon from '@iconify/css-svelte';
import '../../css/z/zutc_xbgy.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path class="zutc_xbgy"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="ion:md-remove-circle" {...props}></Icon>
