<script>
import Icon from '@iconify/css-svelte';
import '../../css/g/g8ued2b6r.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":100,"height":100};
const content = `<path class="g8ued2b6r"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="gis:road-map" {...props}></Icon>
