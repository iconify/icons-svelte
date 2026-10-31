<script>
import Icon from '@iconify/css-svelte';
import '../../css/c/c-d7dab2a.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="c-d7dab2a"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="coolicons:letter-o-duotone-round" {...props}></Icon>
