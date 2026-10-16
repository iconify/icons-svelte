<script>
import Icon from '@iconify/css-svelte';
import '../../css/t/t-sroiact.css';
import '../../css/a/a3h9c1bxc.css';
import '../../css/y/y-j487bxe.css';
import '../../css/a/amp2bxb4g.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":20,"height":20};
const content = `<path class="t-sroiact"/><path class="a3h9c1bxc"/><path class="y-j487bxe"/><path class="amp2bxb4g"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="energy-icons:bench-vice-20" {...props}></Icon>
