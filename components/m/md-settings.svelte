<script>
import Icon from '@iconify/css-svelte';
import '../../css/r/rkx1mt1bx.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path class="rkx1mt1bx"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="ion:md-settings" {...props}></Icon>
