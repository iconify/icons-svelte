<script>
import Icon from '@iconify/css-svelte';
import '../../css/x/xn5eo9bqs.css';
import '../../css/c/c50zoybkb.css';
import '../../css/m/mdnhgeb6a.css';
import '../../css/x/xe8wi4bvf.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="xn5eo9bqs"><path class="c50zoybkb"/><path class="mdnhgeb6a"/><path class="xe8wi4bvf"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="matita:heart-pulse" {...props}></Icon>
