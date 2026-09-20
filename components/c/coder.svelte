<script>
import Icon from '@iconify/css-svelte';
import '../../css/y/yf8xf_biu.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="yf8xf_biu"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="thesvg-color:coder" {...props}></Icon>
