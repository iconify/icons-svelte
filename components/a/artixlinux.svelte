<script>
import Icon from '@iconify/css-svelte';
import '../../css/s/s78w2n1mt.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":128,"height":128};
const content = `<path class="s78w2n1mt"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="devicon-plain:artixlinux" {...props}></Icon>
