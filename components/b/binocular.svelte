<script>
import Icon from '@iconify/css-svelte';
import '../../css/h/hntgybcog.css';
import '../../css/y/yle_06b4x.css';
import '../../css/r/r14k82bhm.css';
import '../../css/e/egcu1pv4r.css';
import '../../css/p/pwl9v1bkd.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="hntgybcog"><path class="yle_06b4x"/><path class="r14k82bhm"/><path class="egcu1pv4r"/><path class="pwl9v1bkd"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="streamline-ultimate:binocular" {...props}></Icon>
