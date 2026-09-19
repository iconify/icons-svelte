<script>
import Icon from '@iconify/css-svelte';
import '../../css/h/hu_kyabxq.css';
import '../../css/q/qevuypzfx.css';
import '../../css/m/mkh8dfbqu.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":128,"height":128};
const content = `<path class="hu_kyabxq"/><path class="qevuypzfx"/><path class="mkh8dfbqu"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="devicon:networkx-wordmark" {...props}></Icon>
