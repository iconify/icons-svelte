<script>
import Icon from '@iconify/css-svelte';
import '../../css/a/a9xd_xbzz.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path class="a9xd_xbzz"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="ion:ios-arrow-thin-right" {...props}></Icon>
