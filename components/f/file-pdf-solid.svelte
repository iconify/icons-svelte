<script>
import Icon from '@iconify/css-svelte';
import '../../css/u/uemvpygoy.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":32,"height":32};
const content = `<path class="uemvpygoy"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="la:file-pdf-solid" {...props}></Icon>
