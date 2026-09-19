<script>
import Icon from '@iconify/css-svelte';
import '../../css/k/k0s9xhb8s.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":128,"height":128};
const content = `<path class="k0s9xhb8s"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="devicon-plain:grafanaloki-wordmark" {...props}></Icon>
