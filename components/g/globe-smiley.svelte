<script>
import Icon from '@iconify/css-svelte';
import '../../css/s/sws1y7b5y.css';
import '../../css/a/a8-k6ckwt.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":100,"height":100};
const content = `<path class="sws1y7b5y"/><path class="a8-k6ckwt"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="gis:globe-smiley" {...props}></Icon>
