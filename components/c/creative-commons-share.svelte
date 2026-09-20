<script>
import Icon from '@iconify/css-svelte';
import '../../css/p/pzxuhibwo.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":32,"height":32};
const content = `<path class="pzxuhibwo"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="la:creative-commons-share" {...props}></Icon>
