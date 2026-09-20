<script>
import Icon from '@iconify/css-svelte';
import '../../css/b/bi12bsetm.css';
import '../../css/s/sl_3r4agh.css';
import '../../css/r/r2juzqsgu.css';
import '../../css/h/ha3xd_bqt.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":64,"height":64};
const content = `<g class="bi12bsetm"><rect class="sl_3r4agh"/><circle class="r2juzqsgu"/><path class="ha3xd_bqt"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="thesvg-color:plainsignal" {...props}></Icon>
