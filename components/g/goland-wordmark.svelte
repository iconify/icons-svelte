<script>
import Icon from '@iconify/css-svelte';
import '../../css/b/bq8j2vbxj.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":128,"height":128};
const content = `<path class="bq8j2vbxj"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="devicon-plain:goland-wordmark" {...props}></Icon>
