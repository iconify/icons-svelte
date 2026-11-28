<script>
import Icon from '@iconify/css-svelte';
import '../../css/w/w1sfe70wx.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="w1sfe70wx"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="noviair:monitor" {...props}></Icon>
