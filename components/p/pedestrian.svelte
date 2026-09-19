<script>
import Icon from '@iconify/css-svelte';
import '../../css/i/iseehgmbn.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":100,"height":100};
const content = `<path class="iseehgmbn"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="gis:pedestrian" {...props}></Icon>
