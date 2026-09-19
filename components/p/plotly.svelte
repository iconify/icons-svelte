<script>
import Icon from '@iconify/css-svelte';
import '../../css/y/yoqkbjeqd.css';
import '../../css/c/cpe-z9b0s.css';
import '../../css/d/dj01mremq.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":128,"height":128};
const content = `<path class="yoqkbjeqd"/><path class="cpe-z9b0s"/><path class="dj01mremq"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="devicon:plotly" {...props}></Icon>
