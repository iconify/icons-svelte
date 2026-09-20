<script>
import Icon from '@iconify/css-svelte';
import '../../css/a/aqp_ve-xg.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":15,"height":15};
const content = `<path class="aqp_ve-xg"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="pinhead:bent-tobacco-pipe" {...props}></Icon>
