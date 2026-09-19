<script>
import Icon from '@iconify/css-svelte';
import '../../css/r/rinuwhlnp.css';
import '../../css/b/bshyy_b6k.css';
import '../../css/g/g50eo_bim.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":48,"height":48};
const content = `<g class="rinuwhlnp"><circle class="bshyy_b6k"/><path class="g50eo_bim"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="icon-park:girl-one" {...props}></Icon>
