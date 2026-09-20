<script>
import Icon from '@iconify/css-svelte';
import '../../css/w/we76vsw_m.css';
import '../../css/b/blpilfbkk.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="we76vsw_m"/><path class="blpilfbkk"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="token:neo" {...props}></Icon>
