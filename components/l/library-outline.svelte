<script>
import Icon from '@iconify/css-svelte';
import '../../css/e/eyjklpbqy.css';
import '../../css/t/t_y32l19z.css';
import '../../css/t/tb62sjbsx.css';
import '../../css/m/mf4zhw8on.css';
import '../../css/d/dcil5bbwz.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<rect class="eyjklpbqy"/><path class="t_y32l19z"/><rect class="tb62sjbsx"/><rect class="mf4zhw8on"/><path class="dcil5bbwz"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="ion:library-outline" {...props}></Icon>
