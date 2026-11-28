<script>
import Icon from '@iconify/css-svelte';
import '../../css/f/f6uzsk5wx.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":15,"height":15};
const content = `<path class="f6uzsk5wx"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="pinhead:dispensing-machine" {...props}></Icon>
