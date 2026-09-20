<script>
import Icon from '@iconify/css-svelte';
import '../../css/f/fyxd_0z0f.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":15,"height":15};
const content = `<path class="fyxd_0z0f"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="pinhead:hairy-caterpillar" {...props}></Icon>
