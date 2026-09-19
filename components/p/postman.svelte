<script>
import Icon from '@iconify/css-svelte';
import '../../css/i/i6n-h328k.css';
import '../../css/r/rjwj9migx.css';
import '../../css/d/domzjoixq.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":128,"height":128};
const content = `<path class="i6n-h328k"/><path class="rjwj9migx"/><path class="domzjoixq"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="devicon:postman" {...props}></Icon>
