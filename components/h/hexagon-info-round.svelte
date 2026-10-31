<script>
import Icon from '@iconify/css-svelte';
import '../../css/d/d8q5e8axb.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="d8q5e8axb"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="coolicons:hexagon-info-round" {...props}></Icon>
