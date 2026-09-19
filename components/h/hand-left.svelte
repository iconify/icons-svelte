<script>
import Icon from '@iconify/css-svelte';
import '../../css/c/cy54xbb_g.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="cy54xbb_g"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="bxs:hand-left" {...props}></Icon>
