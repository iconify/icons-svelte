<script>
import Icon from '@iconify/css-svelte';
import '../../css/w/wix1-6b0q.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="wix1-6b0q"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="bx:bx-columns" {...props}></Icon>
