<script>
import Icon from '@iconify/css-svelte';
import '../../css/y/yfk15yb3r.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="yfk15yb3r"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="tdesign:previous-filled" {...props}></Icon>
