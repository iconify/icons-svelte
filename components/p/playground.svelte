<script>
import Icon from '@iconify/css-svelte';
import '../../css/m/mlf6_vbtf.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":50,"height":50};
const content = `<path class="mlf6_vbtf"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="map:playground" {...props}></Icon>
