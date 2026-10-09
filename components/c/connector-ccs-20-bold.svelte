<script>
import Icon from '@iconify/css-svelte';
import '../../css/e/e5i-rfb6g.css';
import '../../css/p/pcvcreaar.css';
import '../../css/c/cotzlwrvw.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":20,"height":20};
const content = `<path class="e5i-rfb6g"/><path class="pcvcreaar"/><path class="cotzlwrvw"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="energy-icons:connector-ccs-20-bold" {...props}></Icon>
