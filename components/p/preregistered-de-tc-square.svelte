<script>
import Icon from '@iconify/css-svelte';
import '../../css/w/wmw0aqb3a.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":448,"height":512};
const content = `<path class="wmw0aqb3a"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="academicons:preregistered-de-tc-square" {...props}></Icon>
