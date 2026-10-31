<script>
import Icon from '@iconify/css-svelte';
import '../../css/j/jc4s6ebod.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="jc4s6ebod"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="coolicons:pencil-ruler-fill-round" {...props}></Icon>
