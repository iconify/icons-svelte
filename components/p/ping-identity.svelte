<script>
import Icon from '@iconify/css-svelte';
import '../../css/b/bi12bsetm.css';
import '../../css/k/k4cn9_4_p.css';
import '../../css/b/betwiacky.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":126,"height":22};
const content = `<g class="bi12bsetm"><path class="k4cn9_4_p"/><path class="betwiacky"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="thesvg-color:ping-identity" {...props}></Icon>
