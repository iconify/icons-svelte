<script>
import Icon from '@iconify/css-svelte';
import '../../css/z/zzjb0rqzb.css';
import '../../css/m/m99ygkb_k.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="zzjb0rqzb"/><path class="m99ygkb_k"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="tdesign:banana-filled" {...props}></Icon>
