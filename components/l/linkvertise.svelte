<script>
import Icon from '@iconify/css-svelte';
import '../../css/z/zh3w6ybnu.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="zh3w6ybnu"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="thesvg:linkvertise" {...props}></Icon>
