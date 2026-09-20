<script>
import Icon from '@iconify/css-svelte';
import '../../css/a/ahs9cdbtz.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":32,"height":32};
const content = `<path class="ahs9cdbtz"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="la:chevron-circle-down-solid" {...props}></Icon>
