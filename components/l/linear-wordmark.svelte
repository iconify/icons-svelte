<script>
import Icon from '@iconify/css-svelte';
import '../../css/k/kc19m5q7r.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":128,"height":128};
const content = `<path clip-rule="evenodd" class="kc19m5q7r"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="devicon-plain:linear-wordmark" {...props}></Icon>
