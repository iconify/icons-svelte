<script>
import Icon from '@iconify/css-svelte';
import '../../css/n/nsfig2t_x.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="nsfig2t_x"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="tdesign:desktop-1-filled" {...props}></Icon>
