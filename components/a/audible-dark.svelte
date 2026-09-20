<script>
import Icon from '@iconify/css-svelte';
import '../../css/w/wpvty5shp.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path class="wpvty5shp"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="selfhst:audible-dark" {...props}></Icon>
