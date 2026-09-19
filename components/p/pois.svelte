<script>
import Icon from '@iconify/css-svelte';
import '../../css/d/d7muz-b4d.css';
import '../../css/l/l7pghdblc.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":100,"height":100};
const content = `<path class="d7muz-b4d"/><path class="l7pghdblc"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="gis:pois" {...props}></Icon>
