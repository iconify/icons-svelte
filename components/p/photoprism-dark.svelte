<script>
import Icon from '@iconify/css-svelte';
import '../../css/z/zxcfexb1s.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":283.46,"height":283.46};
const content = `<path class="zxcfexb1s"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="thesvg-color:photoprism-dark" {...props}></Icon>
