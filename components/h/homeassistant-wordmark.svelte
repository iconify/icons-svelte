<script>
import Icon from '@iconify/css-svelte';
import '../../css/h/h2hr1xjqd.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":128,"height":128};
const content = `<path class="h2hr1xjqd"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="devicon-plain:homeassistant-wordmark" {...props}></Icon>
