<script>
import Icon from '@iconify/css-svelte';
import '../../css/b/bn2830bka.css';
import '../../css/v/vgycreacb.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":100,"height":100};
const content = `<path class="bn2830bka"/><path class="vgycreacb"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="gis:layer-stat-alt" {...props}></Icon>
