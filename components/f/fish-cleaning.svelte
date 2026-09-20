<script>
import Icon from '@iconify/css-svelte';
import '../../css/h/hdckdr6_d.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":50,"height":50};
const content = `<path class="hdckdr6_d"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="map:fish-cleaning" {...props}></Icon>
