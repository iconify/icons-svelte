<script>
import Icon from '@iconify/css-svelte';
import '../../css/h/hit3bi0-v.css';
import '../../css/m/muhpohbqa.css';
import '../../css/d/dddng97uq.css';
import '../../css/r/r4lh1ibfe.css';
import '../../css/q/qkiuolbwp.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":48,"height":48};
const content = `<g class="hit3bi0-v"><path class="muhpohbqa"/><path class="dddng97uq"/><path class="r4lh1ibfe"/><path class="qkiuolbwp"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="icon-park-outline:riding-one" {...props}></Icon>
