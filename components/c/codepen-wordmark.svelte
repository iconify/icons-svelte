<script>
import Icon from '@iconify/css-svelte';
import '../../css/h/hsrw1rmue.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":128,"height":128};
const content = `<path class="hsrw1rmue"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="devicon:codepen-wordmark" {...props}></Icon>
