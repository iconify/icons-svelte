<script>
import Icon from '@iconify/css-svelte';
import '../../css/y/yujzi7b_c.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path class="yujzi7b_c"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="ion:md-link" {...props}></Icon>
