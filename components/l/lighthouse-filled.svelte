<script>
import Icon from '@iconify/css-svelte';
import '../../css/y/yzdorlbmv.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="yzdorlbmv"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="griddy-icons:lighthouse-filled" {...props}></Icon>
