<script>
import Icon from '@iconify/css-svelte';
import '../../css/w/wv5q1vbak.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="wv5q1vbak"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="thesvg-color:dbeaver" {...props}></Icon>
