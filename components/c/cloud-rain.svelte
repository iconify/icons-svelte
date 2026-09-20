<script>
import Icon from '@iconify/css-svelte';
import '../../css/t/t-upshjrp.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":32,"height":32};
const content = `<path class="t-upshjrp"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="la:cloud-rain" {...props}></Icon>
