<script>
import Icon from '@iconify/css-svelte';
import '../../css/b/bee63kb0z.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":128,"height":128};
const content = `<path class="bee63kb0z"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="devicon-plain:css3-wordmark" {...props}></Icon>
