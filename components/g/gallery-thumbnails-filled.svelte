<script>
import Icon from '@iconify/css-svelte';
import '../../css/d/d0fu8dkns.css';
import '../../css/y/y66poj2zc.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<rect class="d0fu8dkns"/><path class="y66poj2zc"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="boxicons:gallery-thumbnails-filled" {...props}></Icon>
