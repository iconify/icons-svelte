<script>
import Icon from '@iconify/css-svelte';
import '../../css/h/hit3bi0-v.css';
import '../../css/a/amzbzxb8s.css';
import '../../css/g/gr93ygbgb.css';
import '../../css/b/bi3icjb1j.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":48,"height":48};
const content = `<g class="hit3bi0-v"><path class="amzbzxb8s"/><path class="gr93ygbgb"/><ellipse class="bi3icjb1j"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="icon-park-outline:french-fries" {...props}></Icon>
