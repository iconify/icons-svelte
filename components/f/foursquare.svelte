<script>
import Icon from '@iconify/css-svelte';
import '../../css/h/hfs6cib_d.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":640,"height":640};
const content = `<path class="hfs6cib_d"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="fa7-brands:foursquare" {...props}></Icon>
