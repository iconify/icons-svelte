<script>
import Icon from '@iconify/css-svelte';
import '../../css/b/bwrlhtdnv.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path class="bwrlhtdnv"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="ion:ios-contact" {...props}></Icon>
