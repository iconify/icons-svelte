<script>
import Icon from '@iconify/css-svelte';
import '../../css/y/ydobuzwvd.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="ydobuzwvd"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="thesvg-color:folo" {...props}></Icon>
