<script>
import Icon from '@iconify/css-svelte';
import '../../css/c/czbj6bb-q.css';
import '../../css/r/rioz_6b_m.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":32,"height":32};
const content = `<path class="czbj6bb-q"/><path class="rioz_6b_m"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="carbon:mail-reply" {...props}></Icon>
