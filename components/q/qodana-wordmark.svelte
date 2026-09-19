<script>
import Icon from '@iconify/css-svelte';
import '../../css/i/idk0c28mv.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":128,"height":128};
const content = `<path class="idk0c28mv"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="devicon-plain:qodana-wordmark" {...props}></Icon>
