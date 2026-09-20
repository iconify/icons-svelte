<script>
import Icon from '@iconify/css-svelte';
import '../../css/p/ps1r537wx.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="ps1r537wx"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="ri:file-info-fill" {...props}></Icon>
