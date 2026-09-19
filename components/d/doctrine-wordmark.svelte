<script>
import Icon from '@iconify/css-svelte';
import '../../css/o/ot3lesm0z.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":128,"height":128};
const content = `<path class="ot3lesm0z"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="devicon-plain:doctrine-wordmark" {...props}></Icon>
