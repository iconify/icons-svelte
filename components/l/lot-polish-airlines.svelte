<script>
import Icon from '@iconify/css-svelte';
import '../../css/y/yy0s0bcut.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="yy0s0bcut"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="thesvg-color:lot-polish-airlines" {...props}></Icon>
