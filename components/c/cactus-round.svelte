<script>
import Icon from '@iconify/css-svelte';
import '../../css/n/n62kol-kt.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="n62kol-kt"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="coolicons:cactus-round" {...props}></Icon>
