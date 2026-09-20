<script>
import Icon from '@iconify/css-svelte';
import '../../css/r/r1phvccex.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="r1phvccex"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="solar:paperclip-rounded-2-linear" {...props}></Icon>
