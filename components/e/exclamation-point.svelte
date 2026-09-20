<script>
import Icon from '@iconify/css-svelte';
import '../../css/x/xqb-0_4ig.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":15,"height":15};
const content = `<path class="xqb-0_4ig"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="pinhead:exclamation-point" {...props}></Icon>
