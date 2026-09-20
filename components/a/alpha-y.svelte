<script>
import Icon from '@iconify/css-svelte';
import '../../css/d/db9x-x-wx.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":22,"height":22};
const content = `<path class="db9x-x-wx"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="memory:alpha-y" {...props}></Icon>
