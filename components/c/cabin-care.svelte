<script>
import Icon from '@iconify/css-svelte';
import '../../css/z/zfrs8ublx.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":32,"height":32};
const content = `<path class="zfrs8ublx"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="carbon:cabin-care" {...props}></Icon>
