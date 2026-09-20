<script>
import Icon from '@iconify/css-svelte';
import '../../css/m/m2ftgfzzo.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":15,"height":15};
const content = `<path class="m2ftgfzzo"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="teenyicons:elbow-connector-outline" {...props}></Icon>
