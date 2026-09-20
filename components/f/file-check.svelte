<script>
import Icon from '@iconify/css-svelte';
import '../../css/h/hntgybcog.css';
import '../../css/u/ud20_tc4b.css';
import '../../css/m/moorkb8oa.css';
import '../../css/m/mz2593bjh.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="hntgybcog"><path class="ud20_tc4b"/><path class="moorkb8oa"/><path class="mz2593bjh"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="mage:file-check" {...props}></Icon>
