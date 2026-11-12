<script>
import Icon from '@iconify/css-svelte';
import '../../css/v/v7pp64bgr.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":128,"height":128};
const content = `<path class="v7pp64bgr"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="devicon-plain:junit-wordmark" {...props}></Icon>
