<script>
import Icon from '@iconify/css-svelte';
import '../../css/q/qyw9ubbcq.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":128,"height":128};
const content = `<path class="qyw9ubbcq"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="devicon-plain:bevyengine-wordmark" {...props}></Icon>
