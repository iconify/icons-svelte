<script>
import Icon from '@iconify/css-svelte';
import '../../css/g/g31-57k7t.css';
import '../../css/b/b35547tna.css';
import '../../css/l/l-5yedzfg.css';
import '../../css/j/j8eet4jdx.css';
import '../../css/w/wdl6pacqh.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":20,"height":20};
const content = `<path class="g31-57k7t"/><path class="b35547tna"/><path class="l-5yedzfg"/><path class="j8eet4jdx"/><path class="wdl6pacqh"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="energy-icons:graphite-20-bold" {...props}></Icon>
