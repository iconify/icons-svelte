<script>
import Icon from '@iconify/css-svelte';
import '../../css/g/gw1f1pl0j.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":48,"height":48};
const content = `<path class="gw1f1pl0j"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="icon-park-outline:one" {...props}></Icon>
