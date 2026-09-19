<script>
import Icon from '@iconify/css-svelte';
import '../../css/s/sa-m42b2p.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":128,"height":128};
const content = `<path class="sa-m42b2p"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="devicon:couchbase" {...props}></Icon>
