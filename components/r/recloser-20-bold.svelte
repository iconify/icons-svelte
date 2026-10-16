<script>
import Icon from '@iconify/css-svelte';
import '../../css/b/bqjo_17sw.css';
import '../../css/b/bxk-0nxsq.css';
import '../../css/w/wtv0jqdvv.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":20,"height":20};
const content = `<path class="bqjo_17sw"/><path class="bxk-0nxsq"/><path class="wtv0jqdvv"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="energy-icons:recloser-20-bold" {...props}></Icon>
