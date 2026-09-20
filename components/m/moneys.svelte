<script>
import Icon from '@iconify/css-svelte';
import '../../css/j/j7fmnlb4r.css';
import '../../css/c/ciziwtbzu.css';
import '../../css/z/zg2kuvbcb.css';
import '../../css/p/p1hhowniu.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="j7fmnlb4r"><path class="ciziwtbzu"/><path class="zg2kuvbcb"/><path class="p1hhowniu"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="reicon:moneys" {...props}></Icon>
