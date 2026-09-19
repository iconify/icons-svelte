<script>
import Icon from '@iconify/css-svelte';
import '../../css/m/m4teavamv.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":128,"height":128};
const content = `<path class="m4teavamv"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="devicon:opensuse-wordmark" {...props}></Icon>
