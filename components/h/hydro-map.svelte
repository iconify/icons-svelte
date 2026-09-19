<script>
import Icon from '@iconify/css-svelte';
import '../../css/g/ghf9evaie.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":100,"height":100};
const content = `<path class="ghf9evaie"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="gis:hydro-map" {...props}></Icon>
