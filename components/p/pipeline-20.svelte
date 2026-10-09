<script>
import Icon from '@iconify/css-svelte';
import '../../css/d/d-adm0bmn.css';
import '../../css/z/zdes4i07z.css';
import '../../css/o/oawqqplkr.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":20,"height":20};
const content = `<path class="d-adm0bmn"/><path class="zdes4i07z"/><path class="oawqqplkr"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="energy-icons:pipeline-20" {...props}></Icon>
