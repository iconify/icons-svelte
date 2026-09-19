<script>
import Icon from '@iconify/css-svelte';
import '../../css/m/mmowpeg6f.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":100,"height":100};
const content = `<path class="mmowpeg6f"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="gis:color" {...props}></Icon>
