<script>
import Icon from '@iconify/css-svelte';
import '../../css/d/dp9qklbmo.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":32,"height":32};
const content = `<path class="dp9qklbmo"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="la:creative-commons-pd-alt" {...props}></Icon>
