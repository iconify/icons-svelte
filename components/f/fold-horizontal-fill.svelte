<script>
import Icon from '@iconify/css-svelte';
import '../../css/j/j-cj6-fya.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="j-cj6-fya"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="mingcute:fold-horizontal-fill" {...props}></Icon>
