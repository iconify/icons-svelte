<script>
import Icon from '@iconify/css-svelte';
import '../../css/n/nk_as72bq.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":32,"height":32};
const content = `<path class="nk_as72bq"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="la:cloud-sun-rain" {...props}></Icon>
