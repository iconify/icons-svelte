<script>
import Icon from '@iconify/css-svelte';
import '../../css/b/bda_-iejr.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":100,"height":100};
const content = `<path class="bda_-iejr"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="gis:layer-2-rm-o" {...props}></Icon>
