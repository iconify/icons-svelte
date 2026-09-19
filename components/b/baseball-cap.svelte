<script>
import Icon from '@iconify/css-svelte';
import '../../css/h/hit3bi0-v.css';
import '../../css/h/ho2pnibko.css';
import '../../css/a/apvo4cjdv.css';
import '../../css/p/p_u5gqrid.css';
import '../../css/v/v9zcxtbjw.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":48,"height":48};
const content = `<g class="hit3bi0-v"><path class="ho2pnibko"/><path class="apvo4cjdv"/><rect class="p_u5gqrid"/><circle class="v9zcxtbjw"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="icon-park-outline:baseball-cap" {...props}></Icon>
