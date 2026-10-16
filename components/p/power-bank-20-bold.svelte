<script>
import Icon from '@iconify/css-svelte';
import '../../css/b/b9wovjvct.css';
import '../../css/s/sx3zuyn8y.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":20,"height":20};
const content = `<path class="b9wovjvct"/><path class="sx3zuyn8y"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="energy-icons:power-bank-20-bold" {...props}></Icon>
