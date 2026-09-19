<script>
import Icon from '@iconify/css-svelte';
import '../../css/y/yf39cbn8y.css';
import '../../css/u/uhsthdc5f.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":100,"height":100};
const content = `<path class="yf39cbn8y"/><path class="uhsthdc5f"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="gis:map-share-alt" {...props}></Icon>
