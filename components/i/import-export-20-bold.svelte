<script>
import Icon from '@iconify/css-svelte';
import '../../css/i/itv0f-bax.css';
import '../../css/n/ncx05ab2q.css';
import '../../css/t/tthe00koa.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":20,"height":20};
const content = `<path class="itv0f-bax"/><path class="ncx05ab2q"/><path class="tthe00koa"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="energy-icons:import-export-20-bold" {...props}></Icon>
