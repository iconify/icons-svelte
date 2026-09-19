<script>
import Icon from '@iconify/css-svelte';
import '../../css/m/m81bi_bfe.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":128,"height":128};
const content = `<path class="m81bi_bfe"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="devicon-plain:opentelemetry-wordmark" {...props}></Icon>
