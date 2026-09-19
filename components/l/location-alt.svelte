<script>
import Icon from '@iconify/css-svelte';
import '../../css/u/u3fekvbmx.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":20,"height":20};
const content = `<path class="u3fekvbmx"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="dashicons:location-alt" {...props}></Icon>
