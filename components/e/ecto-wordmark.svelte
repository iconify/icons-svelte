<script>
import Icon from '@iconify/css-svelte';
import '../../css/n/n6l_j5b2f.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":128,"height":128};
const content = `<path class="n6l_j5b2f"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="devicon-plain:ecto-wordmark" {...props}></Icon>
