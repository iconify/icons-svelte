<script>
import Icon from '@iconify/css-svelte';
import '../../css/h/hntgybcog.css';
import '../../css/z/zatn0nbfw.css';
import '../../css/o/o-6d_8bvb.css';
import '../../css/h/hofyi4b8i.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="hntgybcog"><path class="zatn0nbfw"/><path class="o-6d_8bvb"/><path class="hofyi4b8i"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="mynaui:git-diff" {...props}></Icon>
