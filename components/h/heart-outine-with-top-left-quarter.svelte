<script>
import Icon from '@iconify/css-svelte';
import '../../css/d/dv-ticcvy.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":15,"height":15};
const content = `<path class="dv-ticcvy"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="pinhead:heart-outine-with-top-left-quarter" {...props}></Icon>
