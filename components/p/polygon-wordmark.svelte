<script>
import Icon from '@iconify/css-svelte';
import '../../css/m/m7xv-rpmo.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":128,"height":128};
const content = `<path class="m7xv-rpmo"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="devicon-plain:polygon-wordmark" {...props}></Icon>
