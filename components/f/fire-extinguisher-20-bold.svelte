<script>
import Icon from '@iconify/css-svelte';
import '../../css/l/lr0xwjb7c.css';
import '../../css/p/pv2lfsb0a.css';
import '../../css/v/v09rlcbxy.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":20,"height":20};
const content = `<path class="lr0xwjb7c"/><path class="pv2lfsb0a"/><path class="v09rlcbxy"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="energy-icons:fire-extinguisher-20-bold" {...props}></Icon>
