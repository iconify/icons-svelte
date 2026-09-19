<script>
import Icon from '@iconify/css-svelte';
import '../../css/s/su6iesbpu.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":128,"height":128};
const content = `<path class="su6iesbpu"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="devicon:nextjs-wordmark" {...props}></Icon>
