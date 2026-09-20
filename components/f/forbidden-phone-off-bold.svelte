<script>
import Icon from '@iconify/css-svelte';
import '../../css/k/kplff-6wx.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="kplff-6wx"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="streamline-ultimate:forbidden-phone-off-bold" {...props}></Icon>
