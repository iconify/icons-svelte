<script>
import Icon from '@iconify/css-svelte';
import '../../css/u/umxo5vd2l.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":80,"height":80};
const content = `<path class="umxo5vd2l"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="glyphs-poly:question" {...props}></Icon>
