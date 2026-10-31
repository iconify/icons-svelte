<script>
import Icon from '@iconify/css-svelte';
import '../../css/v/vsqu32biu.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="vsqu32biu"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="coolicons:road-round" {...props}></Icon>
