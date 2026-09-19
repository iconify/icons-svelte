<script>
import Icon from '@iconify/css-svelte';
import '../../css/l/ln_xg1opz.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":100,"height":100};
const content = `<path class="ln_xg1opz"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="gis:pois-o" {...props}></Icon>
