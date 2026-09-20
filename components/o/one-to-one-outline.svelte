<script>
import Icon from '@iconify/css-svelte';
import '../../css/p/pzwy4ibwx.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":16,"height":16};
const content = `<path class="pzwy4ibwx"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="lsicon:one-to-one-outline" {...props}></Icon>
