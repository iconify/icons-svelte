<script>
import Icon from '@iconify/css-svelte';
import '../../css/j/j-jd97b7f.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":50,"height":50};
const content = `<path class="j-jd97b7f"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="map:lawyer" {...props}></Icon>
