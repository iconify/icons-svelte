<script>
import Icon from '@iconify/css-svelte';
import '../../css/x/xn5eo9bqs.css';
import '../../css/f/frfk1pw2o.css';
import '../../css/w/wn0pp6ege.css';
import '../../css/h/hcwvzkbxx.css';
import '../../css/z/z9a_vxbrs.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="xn5eo9bqs"><path class="frfk1pw2o"/><path class="wn0pp6ege"/><path class="hcwvzkbxx"/><path class="z9a_vxbrs"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="matita:align-right" {...props}></Icon>
