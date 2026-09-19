<script>
import Icon from '@iconify/css-svelte';
import '../../css/e/exgu2ir-q.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":128,"height":128};
const content = `<path class="exgu2ir-q"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="devicon-plain:envoy-wordmark" {...props}></Icon>
