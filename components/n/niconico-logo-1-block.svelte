<script>
import Icon from '@iconify/css-svelte';
import '../../css/s/s6p_0fbmr.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="s6p_0fbmr"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="streamline-logos:niconico-logo-1-block" {...props}></Icon>
