<script>
import Icon from '@iconify/css-svelte';
import '../../css/e/exq9hec0e.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":128,"height":128};
const content = `<path class="exq9hec0e"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="devicon-plain:intellij-wordmark" {...props}></Icon>
