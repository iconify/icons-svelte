<script>
import Icon from '@iconify/css-svelte';
import '../../css/h/hdvm4wbmz.css';
import '../../css/j/ji70huh2p.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":128,"height":128};
const content = `<path class="hdvm4wbmz"/><path class="ji70huh2p"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="devicon:couchbase-wordmark" {...props}></Icon>
