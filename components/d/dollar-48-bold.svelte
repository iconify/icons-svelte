<script>
import Icon from '@iconify/css-svelte';
import '../../css/d/dgom5jd5t.css';
import '../../css/x/xpq7xwfiv.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":48,"height":48};
const content = `<path class="dgom5jd5t"/><path class="xpq7xwfiv"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="energy-icons:dollar-48-bold" {...props}></Icon>
