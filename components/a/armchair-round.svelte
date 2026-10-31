<script>
import Icon from '@iconify/css-svelte';
import '../../css/b/bvr3t2bex.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="bvr3t2bex"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="coolicons:armchair-round" {...props}></Icon>
