<script>
import Icon from '@iconify/css-svelte';
import '../../css/m/mt3wtssut.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="mt3wtssut"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="coolicons:mars-fill-round" {...props}></Icon>
