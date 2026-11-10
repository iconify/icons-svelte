<script>
import Icon from '@iconify/css-svelte';
import '../../css/p/p3pe3fb9r.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":128,"height":128};
const content = `<path class="p3pe3fb9r"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="devicon-plain:nginx-wordmark" {...props}></Icon>
