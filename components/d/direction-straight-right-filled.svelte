<script>
import Icon from '@iconify/css-svelte';
import '../../css/z/zf838kbvj.css';
import '../../css/h/hp757egpp.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":32,"height":32};
const content = `<path class="zf838kbvj"/><path class="hp757egpp"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="carbon:direction-straight-right-filled" {...props}></Icon>
