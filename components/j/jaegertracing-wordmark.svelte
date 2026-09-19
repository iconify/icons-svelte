<script>
import Icon from '@iconify/css-svelte';
import '../../css/k/k9k8yxbjp.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":128,"height":128};
const content = `<path class="k9k8yxbjp"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="devicon-plain:jaegertracing-wordmark" {...props}></Icon>
