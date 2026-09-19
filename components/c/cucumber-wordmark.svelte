<script>
import Icon from '@iconify/css-svelte';
import '../../css/v/vyrluiq9d.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":128,"height":128};
const content = `<path class="vyrluiq9d"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="devicon-plain:cucumber-wordmark" {...props}></Icon>
