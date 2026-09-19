<script>
import Icon from '@iconify/css-svelte';
import '../../css/l/lj1hczbnp.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":128,"height":128};
const content = `<path class="lj1hczbnp"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="devicon-plain:clion-wordmark" {...props}></Icon>
