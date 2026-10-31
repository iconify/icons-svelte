<script>
import Icon from '@iconify/css-svelte';
import '../../css/o/oraqi0b4j.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="oraqi0b4j"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="coolicons:certificate-fill-round" {...props}></Icon>
