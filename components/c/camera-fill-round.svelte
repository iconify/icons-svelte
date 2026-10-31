<script>
import Icon from '@iconify/css-svelte';
import '../../css/n/nfp297bmt.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="nfp297bmt"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="coolicons:camera-fill-round" {...props}></Icon>
