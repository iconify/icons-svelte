<script>
import Icon from '@iconify/css-svelte';
import '../../css/h/hrr0sebxy.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":128,"height":128};
const content = `<path class="hrr0sebxy"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="devicon-plain:nasm-wordmark" {...props}></Icon>
