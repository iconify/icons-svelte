<script>
import Icon from '@iconify/css-svelte';
import '../../css/w/wjtor5_fy.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="wjtor5_fy"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="ri:folder-info-fill" {...props}></Icon>
