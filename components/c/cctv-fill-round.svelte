<script>
import Icon from '@iconify/css-svelte';
import '../../css/f/fkxf86huh.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="fkxf86huh"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="coolicons:cctv-fill-round" {...props}></Icon>
