<script>
import Icon from '@iconify/css-svelte';
import '../../css/a/awr86_bao.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":16,"height":16};
const content = `<path class="awr86_bao"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="lsicon:park-outline" {...props}></Icon>
