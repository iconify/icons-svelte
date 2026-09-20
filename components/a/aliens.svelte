<script>
import Icon from '@iconify/css-svelte';
import '../../css/b/b4neugbts.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":1102,"height":1462};
const content = `<path class="b4neugbts"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="wi:aliens" {...props}></Icon>
