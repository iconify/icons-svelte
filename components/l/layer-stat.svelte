<script>
import Icon from '@iconify/css-svelte';
import '../../css/d/dpos9jrlq.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":100,"height":100};
const content = `<path class="dpos9jrlq"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="gis:layer-stat" {...props}></Icon>
