<script>
import Icon from '@iconify/css-svelte';
import '../../css/r/rinuwhlnp.css';
import '../../css/h/hy_bunouy.css';
import '../../css/k/k36ojmfhz.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":48,"height":48};
const content = `<g class="rinuwhlnp"><path class="hy_bunouy"/><path class="k36ojmfhz"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="icon-park:people" {...props}></Icon>
