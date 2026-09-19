<script>
import Icon from '@iconify/css-svelte';
import '../../css/v/v78z00blh.css';
import '../../css/a/aj0gbdb0u.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":128,"height":128};
const content = `<path class="v78z00blh"/><path class="aj0gbdb0u"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="devicon-plain:arduino-wordmark" {...props}></Icon>
