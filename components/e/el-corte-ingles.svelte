<script>
import Icon from '@iconify/css-svelte';
import '../../css/z/zgihau-wd.css';
import '../../css/s/s5od5637z.css';
import '../../css/o/olmyeubsp.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":1039.699,"height":585.831};
const content = `<path class="zgihau-wd"/><path class="s5od5637z"/><path class="olmyeubsp"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="thesvg-color:el-corte-ingles" {...props}></Icon>
