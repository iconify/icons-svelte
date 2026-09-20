<script>
import Icon from '@iconify/css-svelte';
import '../../css/g/gi53r86ip.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":16,"height":16};
const content = `<path class="gi53r86ip"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="lsicon:constitute-outline" {...props}></Icon>
