<script>
import Icon from '@iconify/css-svelte';
import '../../css/n/nlffeiayp.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="nlffeiayp"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="coolicons:circle-arrow-down-round" {...props}></Icon>
