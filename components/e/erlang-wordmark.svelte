<script>
import Icon from '@iconify/css-svelte';
import '../../css/y/yn8z88y2s.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":128,"height":128};
const content = `<path class="yn8z88y2s"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="devicon-plain:erlang-wordmark" {...props}></Icon>
