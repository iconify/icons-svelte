<script>
import Icon from '@iconify/css-svelte';
import '../../css/b/bozixybsr.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="bozixybsr"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="coolicons:pill-fill-round" {...props}></Icon>
