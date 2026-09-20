<script>
import Icon from '@iconify/css-svelte';
import '../../css/d/dhg-idsjd.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":32,"height":32};
const content = `<path class="dhg-idsjd"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="la:ns8" {...props}></Icon>
