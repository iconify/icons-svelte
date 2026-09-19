<script>
import Icon from '@iconify/css-svelte';
import '../../css/d/d5gzt1b6x.css';
import '../../css/g/g0ghr3b-k.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":128,"height":128};
const content = `<path class="d5gzt1b6x"/><path class="g0ghr3b-k"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="devicon:reactrouter-wordmark" {...props}></Icon>
