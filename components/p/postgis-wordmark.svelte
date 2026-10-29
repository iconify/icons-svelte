<script>
import Icon from '@iconify/css-svelte';
import '../../css/e/eiq-kp2it.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":128,"height":128};
const content = `<path class="eiq-kp2it"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="devicon-plain:postgis-wordmark" {...props}></Icon>
