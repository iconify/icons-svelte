<script>
import Icon from '@iconify/css-svelte';
import '../../css/t/tzlvgiczh.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="tzlvgiczh"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="streamline-ultimate:radiology-scanner-bold" {...props}></Icon>
