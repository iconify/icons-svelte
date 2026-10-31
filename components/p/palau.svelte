<script>
import Icon from '@iconify/css-svelte';
import '../../css/d/djvu6_z9o.css';
import '../../css/w/wxfft0bkm.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":30,"height":24};
const content = `<path class="djvu6_z9o"/><path class="wxfft0bkm"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="tabler-flags:palau" {...props}></Icon>
