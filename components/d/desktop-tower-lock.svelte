<script>
import Icon from '@iconify/css-svelte';
import '../../css/x/xgzw4tcvt.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="xgzw4tcvt"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="noviair-light:desktop-tower-lock" {...props}></Icon>
