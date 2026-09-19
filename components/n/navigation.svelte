<script>
import Icon from '@iconify/css-svelte';
import '../../css/y/ydzwtpbky.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="ydzwtpbky"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="humbleicons:navigation" {...props}></Icon>
