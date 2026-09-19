<script>
import Icon from '@iconify/css-svelte';
import '../../css/h/hit3bi0-v.css';
import '../../css/s/sq396fsku.css';
import '../../css/d/d6s409x-u.css';
import '../../css/g/g1m7edbey.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":48,"height":48};
const content = `<g class="hit3bi0-v"><path class="sq396fsku"/><path class="d6s409x-u"/><path class="g1m7edbey"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="icon-park-outline:face-recognition" {...props}></Icon>
