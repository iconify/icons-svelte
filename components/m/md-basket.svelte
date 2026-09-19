<script>
import Icon from '@iconify/css-svelte';
import '../../css/h/hgq1ff3gg.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path class="hgq1ff3gg"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="ion:md-basket" {...props}></Icon>
