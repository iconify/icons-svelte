<script>
import Icon from '@iconify/css-svelte';
import '../../css/h/hntgybcog.css';
import '../../css/j/je98fibcj.css';
import '../../css/p/p3wftabhp.css';
import '../../css/k/kt_vqgb8w.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="hntgybcog"><path class="je98fibcj"/><path class="p3wftabhp"/><path class="kt_vqgb8w"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="hugeicons:rainbow" {...props}></Icon>
