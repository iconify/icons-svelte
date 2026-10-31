<script>
import Icon from '@iconify/css-svelte';
import '../../css/u/us3dk9lkn.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="us3dk9lkn"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="withicons:egg-gloss" {...props}></Icon>
