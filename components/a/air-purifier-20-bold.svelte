<script>
import Icon from '@iconify/css-svelte';
import '../../css/a/a27au3gxx.css';
import '../../css/z/zt7ow5bcu.css';
import '../../css/y/yaf3voa5l.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":20,"height":20};
const content = `<path class="a27au3gxx"/><path class="zt7ow5bcu"/><path class="yaf3voa5l"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="energy-icons:air-purifier-20-bold" {...props}></Icon>
