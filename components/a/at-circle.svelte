<script>
import Icon from '@iconify/css-svelte';
import '../../css/z/ze2vclaer.css';
import '../../css/t/tiqlprpox.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path class="ze2vclaer"/><path class="tiqlprpox"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="famicons:at-circle" {...props}></Icon>
