<script>
import Icon from '@iconify/css-svelte';
import '../../css/u/uma6umd4x.css';
import '../../css/u/ua-paobrh.css';
import '../../css/x/xe0_hsbxp.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="uma6umd4x"/><path class="ua-paobrh"/><path class="xe0_hsbxp"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="streamline-ultimate:apk-1-bold" {...props}></Icon>
