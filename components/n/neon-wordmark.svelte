<script>
import Icon from '@iconify/css-svelte';
import '../../css/n/not8szbsj.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":128,"height":128};
const content = `<path class="not8szbsj"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="devicon-plain:neon-wordmark" {...props}></Icon>
