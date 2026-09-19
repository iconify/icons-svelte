<script>
import Icon from '@iconify/css-svelte';
import '../../css/r/r43owfbdf.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="r43owfbdf"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="bxs:area" {...props}></Icon>
