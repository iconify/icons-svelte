<script>
import Icon from '@iconify/css-svelte';
import '../../css/w/wlm1i_1oo.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="wlm1i_1oo"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="keyline-icons:file-video" {...props}></Icon>
