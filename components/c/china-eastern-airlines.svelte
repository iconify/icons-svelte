<script>
import Icon from '@iconify/css-svelte';
import '../../css/v/vn9rd4djt.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="vn9rd4djt"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="thesvg-color:china-eastern-airlines" {...props}></Icon>
