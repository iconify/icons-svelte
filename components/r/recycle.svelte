<script>
import Icon from '@iconify/css-svelte';
import '../../css/w/wdo_zikkl.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="wdo_zikkl"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="bx:recycle" {...props}></Icon>
