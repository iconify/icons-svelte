<script>
import Icon from '@iconify/css-svelte';
import '../../css/m/m68prj4ad.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path class="m68prj4ad"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="fa6-solid:beer-mug-empty" {...props}></Icon>
