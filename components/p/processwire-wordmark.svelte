<script>
import Icon from '@iconify/css-svelte';
import '../../css/e/emlqstweo.css';
import '../../css/s/s-p22fb2s.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":128,"height":128};
const content = `<path class="emlqstweo"/><path class="s-p22fb2s"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="devicon:processwire-wordmark" {...props}></Icon>
