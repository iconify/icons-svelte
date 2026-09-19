<script>
import Icon from '@iconify/css-svelte';
import '../../css/u/uql99-f4j.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":128,"height":128};
const content = `<path class="uql99-f4j"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="devicon-plain:linuxmint-wordmark" {...props}></Icon>
