<script>
import Icon from '@iconify/css-svelte';
import '../../css/k/kk_rkd_or.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="kk_rkd_or"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="mynaui:anchor" {...props}></Icon>
