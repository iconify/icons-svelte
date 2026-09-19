<script>
import Icon from '@iconify/css-svelte';
import '../../css/h/hphpfnr7c.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":1200,"height":1200};
const content = `<path class="hphpfnr7c"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="el:map-marker-alt" {...props}></Icon>
