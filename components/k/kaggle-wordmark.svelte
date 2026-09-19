<script>
import Icon from '@iconify/css-svelte';
import '../../css/m/mjesxm3-v.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":128,"height":128};
const content = `<path class="mjesxm3-v"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="devicon:kaggle-wordmark" {...props}></Icon>
