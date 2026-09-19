<script>
import Icon from '@iconify/css-svelte';
import '../../css/s/sqcj7x-iu.css';
import '../../css/z/zgszk2b4j.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":32,"height":32};
const content = `<path class="sqcj7x-iu"/><path class="zgszk2b4j"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="carbon:play-filled" {...props}></Icon>
