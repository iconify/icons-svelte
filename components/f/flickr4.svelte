<script>
import Icon from '@iconify/css-svelte';
import '../../css/p/pcbic_sri.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":16,"height":16};
const content = `<path class="pcbic_sri"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="icomoon-free:flickr4" {...props}></Icon>
