<script>
import Icon from '@iconify/css-svelte';
import '../../css/p/pvo81jd5y.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path class="pvo81jd5y"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="ion:md-share-alt" {...props}></Icon>
