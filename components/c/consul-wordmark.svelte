<script>
import Icon from '@iconify/css-svelte';
import '../../css/s/s6x24cc9z.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":128,"height":128};
const content = `<path class="s6x24cc9z"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="devicon-plain:consul-wordmark" {...props}></Icon>
