<script>
import Icon from '@iconify/css-svelte';
import '../../css/a/aovi3obji.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="aovi3obji"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="coolicons:circle-dot-fill-round" {...props}></Icon>
