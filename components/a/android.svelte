<script>
import Icon from '@iconify/css-svelte';
import '../../css/l/lsc2t133k.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="lsc2t133k"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="streamline-cyber:android" {...props}></Icon>
