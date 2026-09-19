<script>
import Icon from '@iconify/css-svelte';
import '../../css/h/hit3bi0-v.css';
import '../../css/i/ii0wlebwq.css';
import '../../css/t/tq02k9b6e.css';
import '../../css/m/mujmwlp-j.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":48,"height":48};
const content = `<g class="hit3bi0-v"><path class="ii0wlebwq"/><ellipse class="tq02k9b6e"/><path class="mujmwlp-j"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="icon-park-outline:future-build-two" {...props}></Icon>
