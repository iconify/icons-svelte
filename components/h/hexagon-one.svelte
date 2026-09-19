<script>
import Icon from '@iconify/css-svelte';
import '../../css/g/gx_4j-mjb.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":48,"height":48};
const content = `<path class="gx_4j-mjb"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="icon-park-outline:hexagon-one" {...props}></Icon>
