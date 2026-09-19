<script>
import Icon from '@iconify/css-svelte';
import '../../css/b/bi12bsetm.css';
import '../../css/k/krlql_bjj.css';
import '../../css/g/g20mbbbvd.css';
import '../../css/j/j8rvdj99s.css';
import '../../css/r/rqcwvnpsb.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":32,"height":24};
const content = `<g clip-rule="evenodd" class="bi12bsetm"><path class="krlql_bjj"/><path class="g20mbbbvd"/><path class="j8rvdj99s"/><path class="rqcwvnpsb"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="flagpack:lc" {...props}></Icon>
