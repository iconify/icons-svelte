<script>
import Icon from '@iconify/css-svelte';
import '../../css/a/atyzbqqte.css';
import '../../css/l/lqtxhpbhh.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":128,"height":128};
const content = `<path class="atyzbqqte"/><path class="lqtxhpbhh"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="devicon:ecto-wordmark" {...props}></Icon>
