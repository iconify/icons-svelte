<script>
import Icon from '@iconify/css-svelte';
import '../../css/f/ft5dv1b6b.css';
import '../../css/k/k7245g1tp.css';
import '../../css/z/zvafccczm.css';
import '../../css/m/mq5xx16sw.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":48,"height":48};
const content = `<g class="ft5dv1b6b"><rect class="k7245g1tp"/><path class="zvafccczm"/><rect transform="rotate(90 15 29)" class="mq5xx16sw"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="icon-park:painted-screen" {...props}></Icon>
