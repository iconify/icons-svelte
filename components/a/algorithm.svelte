<script>
import Icon from '@iconify/css-svelte';
import '../../css/h/hntgybcog.css';
import '../../css/b/bd77njbqt.css';
import '../../css/y/y__863ctc.css';
import '../../css/c/cv06d6bir.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="hntgybcog"><path class="bd77njbqt"/><path class="y__863ctc"/><path class="cv06d6bir"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="hugeicons:algorithm" {...props}></Icon>
