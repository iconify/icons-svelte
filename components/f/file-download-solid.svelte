<script>
import Icon from '@iconify/css-svelte';
import '../../css/p/ppzu5_91m.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":32,"height":32};
const content = `<path class="ppzu5_91m"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="la:file-download-solid" {...props}></Icon>
