<script>
import Icon from '@iconify/css-svelte';
import '../../css/e/et_33pbys.css';
import '../../css/n/n2ffv50qs.css';
import '../../css/p/p2kzhab-j.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":20,"height":20};
const content = `<path class="et_33pbys"/><path class="n2ffv50qs"/><path class="p2kzhab-j"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="energy-icons:heat-meter-20" {...props}></Icon>
