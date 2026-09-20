<script>
import Icon from '@iconify/css-svelte';
import '../../css/s/sn62dvbtd.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":16,"height":16};
const content = `<path class="sn62dvbtd"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="lsicon:check-correct-outline" {...props}></Icon>
