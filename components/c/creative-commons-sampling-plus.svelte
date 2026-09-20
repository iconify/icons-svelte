<script>
import Icon from '@iconify/css-svelte';
import '../../css/a/aavp4xb5r.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":32,"height":32};
const content = `<path class="aavp4xb5r"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="la:creative-commons-sampling-plus" {...props}></Icon>
