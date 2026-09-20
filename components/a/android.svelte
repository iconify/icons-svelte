<script>
import Icon from '@iconify/css-svelte';
import '../../css/z/zfww3p6yv.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":32,"height":32};
const content = `<path class="zfww3p6yv"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="la:android" {...props}></Icon>
