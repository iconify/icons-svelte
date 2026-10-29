<script>
import Icon from '@iconify/css-svelte';
import '../../css/k/k9wx0431p.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="k9wx0431p"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="withicons:paperclip-duo" {...props}></Icon>
