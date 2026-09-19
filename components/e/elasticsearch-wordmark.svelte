<script>
import Icon from '@iconify/css-svelte';
import '../../css/a/ameq29b2m.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":128,"height":128};
const content = `<path class="ameq29b2m"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="devicon-plain:elasticsearch-wordmark" {...props}></Icon>
