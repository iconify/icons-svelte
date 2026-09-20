<script>
import Icon from '@iconify/css-svelte';
import '../../css/h/hyeaw4bia.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":50,"height":50};
const content = `<path class="hyeaw4bia"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="map:dentist" {...props}></Icon>
