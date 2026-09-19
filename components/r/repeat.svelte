<script>
import Icon from '@iconify/css-svelte';
import '../../css/m/medlfouzc.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":384,"height":432};
const content = `<path class="medlfouzc"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="zmdi:repeat" {...props}></Icon>
