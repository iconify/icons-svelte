<script>
import Icon from '@iconify/css-svelte';
import '../../css/x/x2twmofqo.css';
import '../../css/x/xsfvsus8l.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":128,"height":128};
const content = `<path class="x2twmofqo"/><path class="xsfvsus8l"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="devicon:nasm-wordmark" {...props}></Icon>
