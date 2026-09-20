<script>
import Icon from '@iconify/css-svelte';
import '../../css/a/avu3_us6d.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":20,"height":20};
const content = `<path class="avu3_us6d"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="zondicons:badge" {...props}></Icon>
