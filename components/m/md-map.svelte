<script>
import Icon from '@iconify/css-svelte';
import '../../css/r/r01fabc7a.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path class="r01fabc7a"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="ion:md-map" {...props}></Icon>
