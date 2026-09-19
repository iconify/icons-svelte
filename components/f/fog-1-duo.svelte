<script>
import Icon from '@iconify/css-svelte';
import '../../css/s/snt-orb5x.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":80,"height":80};
const content = `<path class="snt-orb5x"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="glyphs:fog-1-duo" {...props}></Icon>
