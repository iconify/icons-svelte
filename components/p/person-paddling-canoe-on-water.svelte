<script>
import Icon from '@iconify/css-svelte';
import '../../css/l/l_88s3cmp.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":15,"height":15};
const content = `<path class="l_88s3cmp"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="pinhead:person-paddling-canoe-on-water" {...props}></Icon>
