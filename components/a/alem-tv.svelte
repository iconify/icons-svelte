<script>
import Icon from '@iconify/css-svelte';
import '../../css/d/djqqkvfyd.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":145,"height":147};
const content = `<path class="djqqkvfyd"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="thesvg-color:alem-tv" {...props}></Icon>
