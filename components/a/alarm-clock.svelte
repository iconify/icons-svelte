<script>
import Icon from '@iconify/css-svelte';
import '../../css/v/vq4had1wx.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="vq4had1wx"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="noviair-light:alarm-clock" {...props}></Icon>
