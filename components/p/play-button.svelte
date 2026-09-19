<script>
import Icon from '@iconify/css-svelte';
import '../../css/s/s6cy3ybaq.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="s6cy3ybaq"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="gg:play-button" {...props}></Icon>
