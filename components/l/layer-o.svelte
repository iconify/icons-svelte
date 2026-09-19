<script>
import Icon from '@iconify/css-svelte';
import '../../css/t/tj0k-5wrv.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":100,"height":100};
const content = `<path class="tj0k-5wrv"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="gis:layer-o" {...props}></Icon>
