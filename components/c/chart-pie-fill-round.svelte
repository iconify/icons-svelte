<script>
import Icon from '@iconify/css-svelte';
import '../../css/c/cd560hbwb.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="cd560hbwb"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="coolicons:chart-pie-fill-round" {...props}></Icon>
