<script>
import Icon from '@iconify/css-svelte';
import '../../css/h/hit3bi0-v.css';
import '../../css/r/rqnd9ac-f.css';
import '../../css/r/rdtq9xb-o.css';
import '../../css/e/ecnlh9tzj.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":48,"height":48};
const content = `<g class="hit3bi0-v"><path class="rqnd9ac-f"/><path class="rdtq9xb-o"/><path class="ecnlh9tzj"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="icon-park-outline:incoming" {...props}></Icon>
