<script>
import Icon from '@iconify/css-svelte';
import '../../css/r/rs4vcfb4b.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="rs4vcfb4b"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="vadivam:align-center-vertical" {...props}></Icon>
