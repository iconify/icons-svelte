<script>
import Icon from '@iconify/css-svelte';
import '../../css/r/r77b2tbey.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":32,"height":32};
const content = `<path class="r77b2tbey"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="la:hand-peace-solid" {...props}></Icon>
