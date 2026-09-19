<script>
import Icon from '@iconify/css-svelte';
import '../../css/s/stwt57bkp.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":128,"height":128};
const content = `<path class="stwt57bkp"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="devicon-plain:k3s-wordmark" {...props}></Icon>
