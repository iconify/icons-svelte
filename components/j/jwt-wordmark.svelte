<script>
import Icon from '@iconify/css-svelte';
import '../../css/w/w0k8d5yut.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":128,"height":128};
const content = `<path class="w0k8d5yut"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="devicon-plain:jwt-wordmark" {...props}></Icon>
