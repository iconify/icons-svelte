<script>
import Icon from '@iconify/css-svelte';
import '../../css/y/yuw50bchd.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="yuw50bchd"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="reicon:element-plus-filled" {...props}></Icon>
