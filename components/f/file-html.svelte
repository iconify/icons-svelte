<script>
import Icon from '@iconify/css-svelte';
import '../../css/v/vft2j0bsj.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="vft2j0bsj"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="bxs:file-html" {...props}></Icon>
