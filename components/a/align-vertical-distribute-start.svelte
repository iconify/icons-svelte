<script>
import Icon from '@iconify/css-svelte';
import '../../css/n/n3_iqvbak.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="n3_iqvbak"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="pixelarticons:align-vertical-distribute-start" {...props}></Icon>
