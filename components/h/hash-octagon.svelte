<script>
import Icon from '@iconify/css-svelte';
import '../../css/d/d2y0pg1mr.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="d2y0pg1mr"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="mynaui:hash-octagon" {...props}></Icon>
