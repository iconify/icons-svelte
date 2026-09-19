<script>
import Icon from '@iconify/css-svelte';
import '../../css/j/jyfe__5ov.css';
import '../../css/i/izee4xbjj.css';
import '../../css/t/tdt98o_hr.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path class="jyfe__5ov"/><path class="izee4xbjj"/><path class="tdt98o_hr"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="fxemoji:cactus" {...props}></Icon>
