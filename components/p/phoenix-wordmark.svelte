<script>
import Icon from '@iconify/css-svelte';
import '../../css/h/h9hqo-dhv.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":128,"height":128};
const content = `<path class="h9hqo-dhv"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="devicon-plain:phoenix-wordmark" {...props}></Icon>
