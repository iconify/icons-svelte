<script>
import Icon from '@iconify/css-svelte';
import '../../css/l/lk75zkjgm.css';
import '../../css/s/so77q_bes.css';
import '../../css/y/ylah79bhu.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":16,"height":16};
const content = `<path clip-rule="evenodd" class="lk75zkjgm"/><path clip-rule="evenodd" class="so77q_bes"/><path class="ylah79bhu"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="qlementine-icons:music-score-16" {...props}></Icon>
