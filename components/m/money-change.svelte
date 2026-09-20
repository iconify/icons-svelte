<script>
import Icon from '@iconify/css-svelte';
import '../../css/j/j7fmnlb4r.css';
import '../../css/c/cgr1x68jz.css';
import '../../css/t/thwmd5b0c.css';
import '../../css/k/kh50enb1g.css';
import '../../css/e/ekm4kebms.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="j7fmnlb4r"><path class="cgr1x68jz"/><path class="thwmd5b0c"/><path class="kh50enb1g"/><path class="ekm4kebms"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="reicon:money-change" {...props}></Icon>
