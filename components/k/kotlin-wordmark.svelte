<script>
import Icon from '@iconify/css-svelte';
import '../../css/q/qp-3b16-x.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":128,"height":128};
const content = `<path class="qp-3b16-x"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="devicon-plain:kotlin-wordmark" {...props}></Icon>
