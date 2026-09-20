<script>
import Icon from '@iconify/css-svelte';
import '../../css/u/urgydkccf.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":50,"height":50};
const content = `<path class="urgydkccf"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="temaki:amusement-park" {...props}></Icon>
