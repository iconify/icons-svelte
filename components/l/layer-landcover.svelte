<script>
import Icon from '@iconify/css-svelte';
import '../../css/q/qdp7dm02j.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":100,"height":100};
const content = `<path class="qdp7dm02j"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="gis:layer-landcover" {...props}></Icon>
