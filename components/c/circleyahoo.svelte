<script>
import Icon from '@iconify/css-svelte';
import '../../css/e/exslbg_5e.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":1024,"height":1024};
const content = `<path class="exslbg_5e"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="whh:circleyahoo" {...props}></Icon>
