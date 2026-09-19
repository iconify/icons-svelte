<script>
import Icon from '@iconify/css-svelte';
import '../../css/e/erd8cq3wx.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="erd8cq3wx"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="ci:folder-search" {...props}></Icon>
