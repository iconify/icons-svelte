<script>
import Icon from '@iconify/css-svelte';
import '../../css/w/wh1bo_vog.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="wh1bo_vog"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="mynaui:arrow-right" {...props}></Icon>
