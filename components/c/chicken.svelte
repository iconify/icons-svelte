<script>
import Icon from '@iconify/css-svelte';
import '../../css/m/mg_d14xro.css';
import '../../css/h/hube6c-_l.css';
import '../../css/u/u7vstwb-v.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":1024,"height":1024};
const content = `<g display="block"><path class="mg_d14xro"/><path class="hube6c-_l"/><path class="u7vstwb-v"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="iconito:chicken" {...props}></Icon>
