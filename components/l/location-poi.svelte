<script>
import Icon from '@iconify/css-svelte';
import '../../css/s/stgrhqeqj.css';
import '../../css/k/k1_3dpb1f.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":100,"height":100};
const content = `<path class="stgrhqeqj"/><path class="k1_3dpb1f"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="gis:location-poi" {...props}></Icon>
