<script>
import Icon from '@iconify/css-svelte';
import '../../css/o/oik8_tbep.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path class="oik8_tbep"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="ion:md-tablet-landscape" {...props}></Icon>
