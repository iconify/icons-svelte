<script>
import Icon from '@iconify/css-svelte';
import '../../css/s/ssmhtj23q.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path class="ssmhtj23q"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="ion:android-arrow-dropright-circle" {...props}></Icon>
