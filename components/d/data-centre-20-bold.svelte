<script>
import Icon from '@iconify/css-svelte';
import '../../css/a/a_nc-k5jc.css';
import '../../css/b/b9b858bmv.css';
import '../../css/t/tplhgkhuc.css';
import '../../css/l/lupdytbsv.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":20,"height":20};
const content = `<path class="a_nc-k5jc"/><path class="b9b858bmv"/><path class="tplhgkhuc"/><path class="lupdytbsv"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="energy-icons:data-centre-20-bold" {...props}></Icon>
