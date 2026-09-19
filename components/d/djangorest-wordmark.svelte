<script>
import Icon from '@iconify/css-svelte';
import '../../css/q/qxz3oytdu.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":128,"height":128};
const content = `<path class="qxz3oytdu"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="devicon-plain:djangorest-wordmark" {...props}></Icon>
