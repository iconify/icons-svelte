<script>
import Icon from '@iconify/css-svelte';
import '../../css/p/pga_3pelc.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":896,"height":1024};
const content = `<path class="pga_3pelc"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="whh:fonthandwriting" {...props}></Icon>
