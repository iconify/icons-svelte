<script>
import Icon from '@iconify/css-svelte';
import '../../css/d/dyf1f2g-v.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":128,"height":128};
const content = `<path class="dyf1f2g-v"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="devicon-plain:awk-wordmark" {...props}></Icon>
