<script>
import Icon from '@iconify/css-svelte';
import '../../css/h/hntgybcog.css';
import '../../css/w/w6_b8q_9v.css';
import '../../css/r/rvuj5tb-l.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="hntgybcog"><path class="w6_b8q_9v"/><rect class="rvuj5tb-l"/><rect class="rvuj5tb-l"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="stash:pagination-solid" {...props}></Icon>
