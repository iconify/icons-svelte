<script>
import Icon from '@iconify/css-svelte';
import '../../css/b/bki3sv5ox.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":128,"height":128};
const content = `<path clip-rule="evenodd" class="bki3sv5ox"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="devicon-plain:n8n-wordmark" {...props}></Icon>
