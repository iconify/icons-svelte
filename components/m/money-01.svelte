<script>
import Icon from '@iconify/css-svelte';
import '../../css/h/hntgybcog.css';
import '../../css/e/esk48yngh.css';
import '../../css/s/sjwyhhial.css';
import '../../css/t/tl_x59b9b.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="hntgybcog"><path class="esk48yngh"/><path class="sjwyhhial"/><path class="tl_x59b9b"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="hugeicons:money-01" {...props}></Icon>
