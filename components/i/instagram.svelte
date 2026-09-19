<script>
import Icon from '@iconify/css-svelte';
import '../../css/n/nmoyf02wx.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="nmoyf02wx"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="griddy-icons:instagram" {...props}></Icon>
