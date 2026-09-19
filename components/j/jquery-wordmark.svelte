<script>
import Icon from '@iconify/css-svelte';
import '../../css/v/vy1qvyszu.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":128,"height":128};
const content = `<path class="vy1qvyszu"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="devicon-plain:jquery-wordmark" {...props}></Icon>
