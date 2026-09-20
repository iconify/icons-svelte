<script>
import Icon from '@iconify/css-svelte';
import '../../css/m/mfk_7v6jd.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":15,"height":15};
const content = `<path class="mfk_7v6jd"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="pinhead:globe-gasoline-pump-with-droplet" {...props}></Icon>
