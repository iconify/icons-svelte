<script>
import Icon from '@iconify/css-svelte';
import '../../css/z/zx8f4jktk.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path class="zx8f4jktk"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="ion:md-color-filter" {...props}></Icon>
