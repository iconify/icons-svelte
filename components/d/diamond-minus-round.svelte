<script>
import Icon from '@iconify/css-svelte';
import '../../css/x/xsouho3oe.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="xsouho3oe"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="coolicons:diamond-minus-round" {...props}></Icon>
