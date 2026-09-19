<script>
import Icon from '@iconify/css-svelte';
import '../../css/q/q9gx0vbsu.css';
import '../../css/k/kphlzacfd.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":128,"height":128};
const content = `<path class="q9gx0vbsu"/><path class="kphlzacfd"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="devicon:magento-wordmark" {...props}></Icon>
