<script>
import Icon from '@iconify/css-svelte';
import '../../css/z/zebtg939x.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":32,"height":32};
const content = `<path class="zebtg939x"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="la:pen-fancy-solid" {...props}></Icon>
