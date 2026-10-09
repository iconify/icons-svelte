<script>
import Icon from '@iconify/css-svelte';
import '../../css/x/xok_3nz5k.css';
import '../../css/t/t2sid5ean.css';
import '../../css/k/k40br8m-h.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":20,"height":20};
const content = `<path class="xok_3nz5k"/><path class="t2sid5ean"/><path class="k40br8m-h"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="energy-icons:co2-storage-20" {...props}></Icon>
