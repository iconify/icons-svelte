<script>
import Icon from '@iconify/css-svelte';
import '../../css/l/lc5uwbcjl.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path class="lc5uwbcjl"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="ion:football" {...props}></Icon>
