<script>
import Icon from '@iconify/css-svelte';
import '../../css/d/dj_t_y_1r.css';
import '../../css/l/lm83njutd.css';
import '../../css/a/a1qgftbsv.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":128,"height":128};
const content = `<path class="dj_t_y_1r"/><path class="lm83njutd"/><path class="a1qgftbsv"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="devicon:lua" {...props}></Icon>
