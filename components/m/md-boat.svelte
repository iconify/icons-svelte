<script>
import Icon from '@iconify/css-svelte';
import '../../css/o/ol18m9l3x.css';
import '../../css/r/rhyynac5v.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path class="ol18m9l3x"/><path class="rhyynac5v"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="ion:md-boat" {...props}></Icon>
