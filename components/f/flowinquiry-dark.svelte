<script>
import Icon from '@iconify/css-svelte';
import '../../css/b/bk5v1wbtf.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path class="bk5v1wbtf"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="selfhst:flowinquiry-dark" {...props}></Icon>
