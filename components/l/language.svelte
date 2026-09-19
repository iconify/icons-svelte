<script>
import Icon from '@iconify/css-svelte';
import '../../css/m/mgqdux_eq.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":1536,"height":1792};
const content = `<path class="mgqdux_eq"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="fa:language" {...props}></Icon>
