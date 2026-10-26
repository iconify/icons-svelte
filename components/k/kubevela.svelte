<script>
import Icon from '@iconify/css-svelte';
import '../../css/n/n772iyb3h.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":122.5,"height":122.5};
const content = `<path class="n772iyb3h"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="thesvg:kubevela" {...props}></Icon>
